<script lang="ts">
	import { Code, Slide, FormsDraw } from '@components'
	import Media from '@lib/components/media.svelte'

	let howMany
	let results = []
	async function handleSubmit(e) {
		e.preventDefault()
		fetch(
			`https://random-data-api.com/api/v2/${selectedEntity}?size=${howMany}&response_type=json`
		)
			.then((res) => res.json())
			.then((data) => {
				console.log(JSON.stringify(data, null, 2))
				results = data
			})
	}
	let entities = [
		{ name: 'Users', value: 'users' },
		{ name: 'Beers', value: 'beers' },
		{ name: 'Banks', value: 'banks' },
		{ name: 'Appliances', value: 'appliances' },
		{ name: 'Address', value: 'address' },
		{ name: 'Blood Types', value: 'blood_types' },
		{ name: 'Credit Cards', value: 'credit_cards' },
	]
	let selectedEntity;
</script>

<Slide>
	<h1 class="text-7xl font-black">Forms</h1>
	<div data-id="1" class="mx-auto max-w-xl">
		<FormsDraw />
	</div>
</Slide>

<Slide>
	<h1 class="text-7xl font-black">Forms</h1>
	<!-- <div data-id="1" class="mx-auto max-w-xl">
		<FormsDraw />
	</div> -->
	<Media src="/form-elements.png" type="img" class="w-full h-full">

	</Media>
</Slide>


<Slide animate>
	<div class="flex max-h-[90vh] h-[60vh] w-full gap-10">
		<div
			class="form w-1/2 text-base text-black text-left font-bold bg-slate-200 flex flex-col justify-between items-center rounded-xl p-2"
		>
			<h1
				class="flex-grow text-2xl font-black mb-5 pb-5 border-b-4 border-slate-400 w-full text-center"
			>
				{'<form method="POST" action="/">'}
			</h1>
			<form
				method="POST"
				on:submit|preventDefault={handleSubmit}
				action="https://random-data-api.com/api/v2/beers/"
				class="flex flex-col gap-5 h-full justify-between items-center w-full"
			>
				<div class="flex flex-col w-full justify-center items-center flex-grow gap-4">
					<label for="entity" class="flex flex-col w-4/5">
							{'<select>'}...{'<option value="beers" /> </select>'}: {selectedEntity}
						<select
							name="entity"
							id="entity"
							bind:value={selectedEntity}
							class="py-1 px-2 w-full text-sm rounded-md bg-white text-black/70"
						>
							<option selected value="">select what you need</option>
							{#each entities as entity}
								<option value={entity.value}>{entity.name}</option>
							{/each}
						</select>
					</label>
					<label for="how-many" class="flex flex-col w-4/5">
							{'<input type="number" name="how-many">'}
						<input
							type="number"
							name="how-many"
							id="how-many"
							placeholder="1 by default"
							bind:value={howMany}
							class="py-1 px-2 w-full text-sm rounded-md"
						/>
					</label>
				</div>
				<button
					type="submit"
					class="py-1 px-2 w-full bg-red-500 text-white rounded-md"
					>Submit</button
				>
			</form>
		</div>
		<div id="data-container" class="w-1/2 flex-grow h-full overflow-y-scroll">
			<!-- <FormsDraw /> -->
			{#key results}
				<Code lang="json">
					{JSON.stringify(results, null, 2)}
				</Code>
			{/key}
		</div>
	</div>
</Slide>

<style>
	/* flip the formsDraw in the x axis */
	[data-id='1'] {
		transform: scaleX(-1);
	}

	/* hide scroll for data-container */
	#data-container::-webkit-scrollbar {
		display: none;
	}

	/* hide scroll for data-container */
	#data-container {
		-ms-overflow-style: none; /* IE and Edge */
		scrollbar-width: none; /* Firefox */
	}
</style>

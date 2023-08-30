<script lang="ts">
    // @ts-nocheck
	import { Slide } from '@components'
	import Media from '@lib/components/media.svelte'
	// If you are using an SVG or other assets, import them here
</script>

<!-- Slide 1: Introduction -->
<Slide>
	<h1 class="font-bold text-4xl mb-4">
		Let's recap what we've learned so far.
	</h1>
	<Media
		src="https://imagedelivery.net/NgoGKblxkYNsaQumWbWliw/a7c84a0c-1236-42bb-359b-ab0e4a9c0d00/public"
		type="img"
		class="h-full w-3/4 mx-auto border-2 mt-10"
	/>
</Slide>
<Slide animate>
	<h1 data-id="1" class="font-bold text-7xl mb-4">Some Stats</h1>
    <p class="!text-2xl">
        And why we are here
    </p>
</Slide>
<!-- Slide 2: Growing Tech Industry -->
<Slide animate>
	<div class="flex flex-col justify-between h-full">
		<h1 data-id="1" class="font-bold text-3xl mb-4">Some Stats</h1>
        <p class="!text-2xl">
            And why we are here
        </p>
		<div class="py-24 sm:py-32">
			<div class="mx-auto max-w-7xl px-6 lg:px-8">
				<dl
					class="grid grid-cols-1 gap-x-8 gap-y-16 text-center lg:grid-cols-3"
				>
					<div data-id="2" class="mx-auto flex max-w-xs flex-col gap-y-4">
						<dt class="text-base leading-7">
							Open jobs for software developers
						</dt>
						<dd
							class="order-first text-3xl font-semibold tracking-tight sm:text-5xl"
						>
							1 million
						</dd>
					</div>
				</dl>
			</div>
		</div>
	</div>
</Slide>
<Slide animate>
	<div class="flex flex-col justify-between h-full">
		<h1 data-id="1" class="font-bold text-3xl mb-4">Some Stats</h1>
        <p class="!text-2xl">
            And why we are here
        </p>
		<div class="py-24 sm:py-32">
			<div class="mx-auto max-w-7xl px-6 lg:px-8">
				<dl
					class="grid grid-cols-1 gap-x-8 gap-y-16 text-center lg:grid-cols-3"
				>
					<div data-id="2" class="mx-auto flex max-w-xs flex-col gap-y-4">
						<dt class="text-base leading-7">
							Open jobs for software developers
						</dt>
						<dd
							class="order-first text-3xl font-semibold tracking-tight sm:text-5xl"
						>
							1 million
						</dd>
					</div>
					<div data-id="3" class="mx-auto flex max-w-xs flex-col gap-y-4">
						<dt class="text-base leading-7">National Web Dev salary</dt>
						<dd
							class="order-first text-3xl font-semibold tracking-tight sm:text-5xl"
						>
							$65k/year
						</dd>
					</div>
					<!-- <div class="mx-auto flex max-w-xs flex-col gap-y-4">
						<dt class="text-base leading-7">After completing a bootcamp</dt>
						<dd
							class="order-first text-3xl font-semibold tracking-tight sm:text-5xl"
						>
							$20k +
						</dd>
					</div> -->
				</dl>
			</div>
		</div>
	</div>
</Slide>
<Slide>
	<div class="flex flex-col justify-between h-full">
		<h1 data-id="1" class="font-bold text-3xl mb-4">Some Stats</h1>
        <p class="!text-2xl">
            And why we are here
        </p>
		<div class="py-24 sm:py-32">
			<div class="mx-auto max-w-7xl px-6 lg:px-8">
				<dl
					class="grid grid-cols-1 gap-x-8 gap-y-16 text-center lg:grid-cols-3"
				>
					<div data-id="2" class="mx-auto flex max-w-xs flex-col gap-y-4">
						<dt class="text-base leading-7">
							Open jobs for software developers
						</dt>
						<dd
							class="order-first text-3xl font-semibold tracking-tight sm:text-5xl"
						>
							1 million
						</dd>
					</div>
					<div data-id="3"  class="mx-auto flex max-w-xs flex-col gap-y-4">
						<dt class="text-base leading-7">National Web Dev salary</dt>
						<dd
							class="order-first text-3xl font-semibold tracking-tight sm:text-5xl"
						>
							$65k/year
						</dd>
					</div>
					<div class="mx-auto flex max-w-xs flex-col gap-y-4">
						<dt class="text-base leading-7">After completing a bootcamp</dt>
						<dd
							class="order-first text-3xl font-semibold tracking-tight sm:text-5xl"
						>
							$20k +
						</dd>
					</div>
				</dl>
			</div>
		</div>
	</div>
</Slide>
<!-- Slide: Tools & Resources -->
<Slide animate>
	<h1 class="font-bold text-2xl mb-4">Tools and Resources</h1>
	<div class="grid grid-cols-2 gap-5">
		<!-- Mandatory Tools -->
		<div data-id="1" class="text-base font-semibold w-full border-2 p-4">
			<h2 class="text-lg mb-2">Mandatory Tools</h2>
			<ul>
				<li>Github.com</li>
				<li>Slack.com (desktop & mobile)</li>
				<li>Codespaces</li>
			</ul>
		</div>
</Slide>
<Slide animate>
	<h1 class="font-bold text-2xl mb-4">Tools and Resources</h1>
	<div class="grid grid-cols-2 gap-5">
		<!-- Mandatory Tools -->
		<div data-id="1" class="text-base font-semibold w-full border-2 p-4">
			<h2 class="text-lg mb-2">Mandatory Tools</h2>
			<ul>
				<li>Github.com</li>
				<li>Slack.com (desktop & mobile)</li>
				<li>Codespaces</li>
			</ul>
		</div>

		<!-- Other Learning Resources -->
		<div data-id="2" class="text-base font-semibold w-full border-2 p-4">
			<h2 class="text-lg mb-2">Other Learning Resources</h2>
			<ul>
				<li>StackOverflow</li>
				<li>w3Schools.com</li>
				<li>Net Ninja JS Tutorial</li>
			</ul>
		</div>
	</div>
</Slide>

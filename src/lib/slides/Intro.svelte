<script>
	// @ts-nocheck

	import { Slide } from '@components'
	import Media from '@lib/components/media.svelte'
	import mendez from '@public/mendez.jpg'
</script>

<!-- Slide: Course Introduction -->
<Slide>
	<div class="flex flex-col gap-5 items-center">
		<h1 data-id="1" class="font-bold text-5xl mb-4">
			Welcome to the Full-Stack Bootcamp!
		</h1>
		<Media
			src="https://images.unsplash.com/photo-1593720213428-28a5b9e94613?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80"
			alt="Mr Mendez"
			type="img"
			class="h-[500px] w-full border-2"
		/>
	</div>
</Slide>
<Slide>
	<div class="flex gap-2 items-center">
		<div class="w-full">
            <h1 class="font-bold text-2xl mb-4 text-left">
            Yarien Mendez (Mendez)
            </h1>
            <div class="border-2 w-full rounded-md pr-2 overflow-hidden bg-slate-800">
                <div class="flex justify-around gap-2">
                    <Media
                        src="https://imagedelivery.net/NgoGKblxkYNsaQumWbWliw/009a3dd3-693f-4f0f-c7a8-73f07a212800/public"
                        alt="Mr Mendez"
                        type="img"
                        class="h-full w-1/2 "
                    />
                    <div class="text-base w-1/2 flex flex-col justify-around mx-auto">
                        <!-- <h2 class="font-semibold">How to reach me</h2> -->
                        <ul class="flex flex-col gap-2 text-left w-fit mx-auto">
                            <li>EMAIL: info@amvestor.com</li>
                            <li>SLACK: @Mr. Mendez</li>
                            <li>PHONE#: (720) 432-9393</li>
                            <li>DISCORD: @mrmendez.dev</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
		<div class="w-full">
            <h1 class="font-bold text-2xl mb-4 text-left">
                Ernesto Smith (Ernesto)
            </h1>
            <div class="border-2 w-full rounded-md pr-2 overflow-hidden bg-slate-800">
                <div class="flex justify-around gap-2">
                    <Media
                        src="https://ca.slack-edge.com/T04MNQB5LHZ-U04RQDJSG3A-9ba471947586-512"
                        alt="Mr Mendez"
                        type="img"
                        class="h-full w-1/2 "
                    />
                    <div class="text-base w-1/2 flex flex-col justify-around mx-auto">
                        <!-- <h2 class="font-semibold">How to reach me</h2> -->
                        <ul class="flex flex-col gap-2 text-center w-fit mx-auto">
                            <li>EMAIL<br> ernesto.smithjr@outlook.com</li>
                            <li>SLACK<br> @Ernesto Smith</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
	</div>
</Slide>

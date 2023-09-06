<script>

	import { Slide, Code } from '@components'
	
</script>

<!-- Slide 1: Title Slide -->
<Slide animate>
	<!-- write the CSS IS AWESOME logo using tailwindcss -->
	<div class="border-[5px] w-[400px] h-fit p-8 space-y-5 mx-auto">
		<h1 class="text-8xl font-bold uppercase text-left">css is</h1>
		<h1 class="text-8xl font-bold text-center uppercase">awesome</h1>
	</div>
</Slide>

<!-- Slide 2: CSS -->
<Slide animate>
	<Code lang="svelte">
		{`
        <script>
          let count = 0
          $: double = count * 2
        </script>
      `}
	</Code>
</Slide>

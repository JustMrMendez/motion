<script>
	import { Slide, Code } from '@components'
</script>

<!-- Slide 1: Title Slide -->
<Slide>
	<p
		class="border-[5px] w-[400px] h-fit p-8 space-y-5 mx-auto text-8xl font-bold uppercase leading-[1.15]"
	>
		css is awesome
	</p>
</Slide>

<!-- Slide 2: CSS -->
<Slide animate>
	<div class="flex">
		<Code data-id="1" lang="html" class="w-1/2" lines="2,11|3-7|8-10">
			{`
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Postcard</title>
		<link rel="stylesheet"
		href="styles.css" />
	</head>
	<body>
		...content
	</body>
</html>
			  `}
		</Code>

		<div class="border-[1px] w-1/2 grid place-content-center">...content</div>
	</div>
</Slide>

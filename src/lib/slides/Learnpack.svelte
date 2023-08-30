<script lang="ts">
	// @ts-nocheck
	import { Media, Slide } from '@components'
</script>

<Slide animate>
	<h1 class="font-bold text-2xl mb-4">What is LearnPack</h1>
	<div class="flex justify-between flex-col items-center gap-5">
		<!-- Explanation about LearnPack -->
		<div class="text-base text-left">
			<p>
				Throughout this course, you'll use LearnPack extensively for coding
				tutorials and exercises.
			</p>
			<ul class="list-disc">
				<li>Interactive Tutorials</li>
				<li>Auto-Graded Exercises</li>
			</ul>
		</div>
		<!-- Visual representation or related media -->
		<div class="w-2/3">
			<Media
				src="https://github.com/breatheco-de/content/blob/master/src/assets/images/learnpack-alert.png?raw=true"
				type="img"
				class="h-full w-full mx-auto"
			/>
		</div>
	</div>
</Slide>

<Slide animate>
	<Media
		src="https://github.com/breatheco-de/content/blob/master/src/assets/images/learnpack-explanation.png?raw=true"
		type="img"
		class="h-full w-full mx-auto"
	/>
</Slide>
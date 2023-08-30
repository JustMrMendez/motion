<script lang="ts">
	import Html from '@lib/slides/Html.svelte'
import Codespaces from './lib/slides/Codespaces.svelte';
	import { Presentation, Slide } from '@components'
	import Intro from '@lib/slides/Intro.svelte'
	import Learnpack from '@lib/slides/Learnpack.svelte'
	import Prework from '@lib/slides/Prework.svelte'
	// If you are using an SVG or other assets, import them here
</script>

<Presentation>
	<Intro />
	<Prework />
	<Codespaces />
	<Learnpack />
	<Html />
</Presentation>

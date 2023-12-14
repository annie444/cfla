<script lang="ts">
	import '../app.postcss';

	// Floating UI for Popups
	import { computePosition, autoUpdate, flip, shift, offset, arrow } from '@floating-ui/dom';
	import { storePopup } from '@skeletonlabs/skeleton';
	storePopup.set({ computePosition, autoUpdate, flip, shift, offset, arrow });
</script>

<svelte:head>
	<link rel="icon" href="https://ceasefire.la/favicon.png" />
	<meta
		name="description"
		content="In Los Angeles, a group of Palestinians, allies, and anti-Zionist Jews have emerged to rally as a collective people for a critical cause: Palestinian safety and liberation."
	/>
	<meta name="robots" content="index,follow" />
	<meta name="googlebot" content="index,follow" />
	<meta name="google" content="nositelinkssearchbox" />
	<meta name="og:title" content="The People's Ceasefire - Los Angeles" />
	<meta
		name="og:description"
		content="In Los Angeles, a group of Palestinians, allies, and anti-Zionist Jews have emerged to rally as a collective people for a critical cause: Palestinian safety and liberation."
	/>
	<meta name="og:image" content="https://ceasefire.la/card.png" />
	<meta name="og:url" content="https://ceasefire.la" />

	<meta name="twitter:title" content="The People's Ceasefire - Los Angeles" />
	<meta
		name="twitter:description"
		content="In Los Angeles, a group of Palestinians, allies, and anti-Zionist Jews have emerged to rally as a collective people for a critical cause: Palestinian safety and liberation."
	/>
	<meta name="twitter:image" content="https://ceasefire.la/card.png" />
	<meta name="twitter:card" content="summary_large_image" />
</svelte:head>
<slot />

<script lang="ts">
	import '@fontsource-variable/montserrat/wght.css';
	import '@fontsource/arvo/700.css';
	import '@fontsource/recursive/400.css';

	import '$lib/style/global.scss';

	import Footer from '$lib/common/Footer.svelte';
	import Header from '$lib/common/Header.svelte';

	let { children } = $props();
</script>

<Header />

{@render children()}

<Footer />

<svelte:head>
	<script src="https://kit.fontawesome.com/a3de05bb60.js" crossorigin="anonymous"></script>
</svelte:head>

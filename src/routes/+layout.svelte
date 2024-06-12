<script>
	import '../app.pcss';
	import Header from './header.svelte';
	import Footer from './footer.svelte';
</script>

<svelte:head>
	<title>Portfolio | Abdur Rehman Shaikh</title>
</svelte:head>

<div class="app">

	<Header />

	<main class="bg-white dark:bg-gray-900" style="min-height: calc(100vh);">
		<slot />
	</main>

	<Footer />

</div>

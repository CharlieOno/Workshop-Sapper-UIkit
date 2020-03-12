<script>
	import Nav from '../components/Nav.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<style>
	main {
		position: relative;
		background-color: white;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>

<Nav />

<main>
	<slot></slot>
	<Footer />
</main>


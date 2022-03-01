<script>
//	import Nav from '../components/Nav.svelte';
	import Header from '../layout/Header.svelte';
	import Footer from '../layout/Footer.svelte'
//	export let segment;
</script>

<style>
</style>

<Header />

<main>
	<slot></slot>
</main>

<Footer />
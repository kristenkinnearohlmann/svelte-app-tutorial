<script>
	import Header from './header.svelte';
	import Nav from './nav.svelte';
	import Footer from './footer.svelte';
</script>

<div class="page-header">
	<Header />
	<Nav />
</div>

<p>This is example</p>
<Footer />

<style>
	.page-header {
		display: flex;
		flex-flow: row nowrap;
	}
</style>

<script>
	import Router from 'svelte-spa-router';
	import Home from './components/Home.svelte';
	import Portfolio from './components/Portfolio.svelte';
</script>

<Router routes={{
	'/': Home,
	'/portfolio': Portfolio
}} />
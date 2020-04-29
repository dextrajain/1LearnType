<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>
<!-- 	 	 -->
<style>
	main {
		box-sizing: border-box;
		position: relative; 
		width:100%;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
	}
</style>

<Nav {segment}/>

<main>
	<slot></slot>
</main>
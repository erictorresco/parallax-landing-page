<script>
	import '../app.css';
	import Header from '../components/Header.svelte';
	import Main from '../components/Main.svelte';
	import Navigation from '../components/Navigation.svelte';
</script>

<div id="parallax">
	<Navigation />
	<Header />
	<Main />
	<slot />
</div>

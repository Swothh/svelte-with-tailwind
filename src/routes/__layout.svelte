<script>
	import Header from '$lib/Static/Header.svelte';
	import '../app.css';
</script>

<Header />
<div class="body-gradient" />

<main>
	<slot />
</main>
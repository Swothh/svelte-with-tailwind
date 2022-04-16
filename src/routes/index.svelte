<script context="module">
	export const prerender = true;

	let text = 'Hello Svelte!',
		title = 'SvelteKit with TailwindCSS | @Swothh';
</script>

<svelte:head>
	<title>{title}</title>
</svelte:head>

<div class="flex flex-col items-center justify-center py-20 w-full">
	<h1 class="text-9xl text-blue-500 font-semibold">{text}</h1>
	<p class="text-center text-white">You can clone this template from the <a class="text-blue-400 hover:text-white transition-all duration-300" target="_blank" href="https://github.com/Swothh/svelte-with-tailwind">Swothh/svelte-with-tailwind</a> repo.</p>
</div>
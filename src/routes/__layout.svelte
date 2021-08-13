<script>
	import '../app.postcss';
</script>

<svelte:head>
	<html lang="en" />
	<title>Svelte, Tailwind and Netlify CMS Boilerplate</title>
</svelte:head>

<div class="p-5 max-w-6xl mx-auto">
	<a href="/"><h1 class="md:text-left text-center text-6xl mb-5">Blog</h1></a>
	<slot />
</div>

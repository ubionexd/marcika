<script context="module">
	export const prerender = true;
</script>

<style>
	:global(body) {
		background-color: #0f172a;
	}

</style>

<svelte:head>
	<title>Sveltest</title>
	<meta name="description" content="Svelte test app" />
</svelte:head>

<section>
	<div class="text-center text-xl font-bold select-none flex justify-center items-center h-screen">
		<div>
			<h1 class="text-[#ff3e00]">SvelteKit</h1>
			<h1 class="text-[#38bdf8]">with TailwindCSS</h1>
			<p class="text-white mt-10 text-sm">Compiled, with no Virtual-DOM and Server-Side rendering.</p>
			<a class="text-gray-400 mt-1 text-sm hover:underline underline-offset-2" href="https://github.com/ubionexd/sveltest">Feel free to use it on your project!</a>
		</div>
	</div>
</section>
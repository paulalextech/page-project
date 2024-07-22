<script>
	import '../app.css';
	import 'iconify-icon';
</script>

<!-- Navbar -->

<section
	id="home"
	class="w-full h-screen flex items-center justify-center sm:py-32 md:flex-row md:space-x-4 md:text-left md:py-28"
>
	<div class="md:w-1/2 md:mt-2">
		<img
			class="rounded-full p-3"
			src="../assets/hero.svg"
			alt="cartoon profile"
			width={500}
			height={400}
		/>
	</div>

	<div class="md:mt-2 md:w-3/5 p-3">
		<h1 class="font-bold sm:text-6xl text-4xl mt-6 md:text-6xl md:mt-0">
			Welcome to my portfolio built using <span class="text-orange-600">Svelte</span> and
			<span class="text-orange-600">SvelteKit.</span>
		</h1>
		<!-- <p class="text-xl mt-4 mb-2 md:text-3xl">
			I'm a Full-Stack Software Developer. I love building things with tech and retro video games!
		</p> -->
	</div>
</section>

<slot />

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.slate.500);
	}
</style>

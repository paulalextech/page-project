<section id="home">
	<h1 class="text-5xl font-semibold text-center">Software Developer</h1>

	<!-- Navbar -->
	<div class="container max-w-6xl mx-auto px-6 py-4 md:px-0">
		<!-- nav.flex.items-center.justify-between.font-bold -->
	</div>

	<div
		class="w-full flex items-center justify-center sm:py-32 md:flex-row md:space-x-4 md:text-left md:py-28"
	>
		<div class="md:w-1/2 md:mt-2">
			<img
				class="rounded-full"
				src="../assets/hero.svg"
				alt="cartoon profile"
				width={400}
				height={400}
			/>
		</div>
	</div>

	<div class="md:mt-2 md:w-3/5 p-3">
		<h1 class="font-bold sm:text-6xl text-4xl mt-6 md:text-6xl md:mt-0">
			Welcome to my portfolio built using Svelte and SvelteKit.
		</h1>
		<p class="text-xl mt-4 mb-2 md:text-3xl">
			I'm a Full-Stack Software Developer. I love building things with tech and retro video games!
		</p>
	</div>

	<!-- <div class="text-5xl pt-5 text-center">"this is where tech stack logos will go"</div> -->

	<div class="flex flex-row gap-4 mb-4 text-5xl pt-5 text-center">
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
	</div>
</section>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.orange.300);
	}
</style>

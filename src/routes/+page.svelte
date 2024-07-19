<section class="bg-orange-300">
	<h1 class="text-5xl font-semibold text-center">Software Developer</h1>

	<div
		class="w-full h-screen flex flex-col text-center items-center justify-center my-10 py-16 sm:py-32 md:flex-row md:space-x-4 md:text-left md:py-28"
	>
		<div class="md:w-1/2 md:mt-2">
			<img
				class="rounded-full width={300} height={300}"
				src="../assets/hero.svg"
				alt="cartoon profile"
			/>
		</div>
	</div>

	<div class=" md:mt-2 md:w-3/5 bg-white p-3">
		<p>Welcome to my portfolio built using Svelte and SvelteKit.</p>
		<p>
			I'm a Full-Stack Software Developer. I love building things with tech and retro video games!
		</p>
	</div>

	<!-- <div class="text-5xl pt-5 text-center">"this is where tech stack logos will go"</div> -->

	<div class="text-5xl pt-5 text-center">
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
		<iconify-icon icon="mdi:react"></iconify-icon>
	</div>

	<style lang="postcss">
		:global(html) {
			background-color: theme(colors.orange.300);
		}
	</style>
</section>

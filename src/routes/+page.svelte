<script>
	import '../app.css';
</script>

<svelte:head>
	<title>Artana</title>
</svelte:head>

<div class="flex min-h-screen flex-col bg-[#1D183A] bg-[url('/bg.webp')] bg-cover bg-no-repeat">
	<main class="mx-auto flex w-full max-w-screen-xl grow flex-col items-center px-6">
		<h1
			class="center mt-16 font-montserrat text-[60px] font-medium text-white md:mt-40 md:text-[100px]"
		>
			Artana
		</h1>
		<h3 class="center mb-12 max-w-lg text-center font-montserrat text-xl text-[#fafafa]">
			WHERE BLOCKCHAIN MEETS SOCIAL ART
		</h3>
		<a
			href="#"
			class="rounded-full bg-gradient-to-r from-[#B82EFF] to-[#00B0A6] px-16 py-5 font-montserrat text-base font-bold text-white hover:from-[#00B0A6] hover:to-[#B82EFF]"
			>Get Started Today</a
		>
		<img
			src="/phone.webp"
			alt="Artana on a phone"
			class="mx-auto mb-16 mt-32 block w-full max-w-[420px]"
		/>
	</main>
	<footer
		class="mx-auto my-4 w-full max-w-screen-xl px-6 text-center font-montserrat text-xs text-white md:text-base"
	>
		Copyright © 2024 Artana. All rights reserved.
	</footer>
</div>

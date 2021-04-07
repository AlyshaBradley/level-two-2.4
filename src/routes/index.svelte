<script>
	import Header from '$lib/Header.svelte';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<Header />
<Nav />

<main class="hero is-large">
	<div class="hero-body has-bg-img">
		<div class="container has-text-centered">
			<button class="button is-large is-dark">Design Heritage</button>
			<button class="button is-large is-dark">Visual Communication</button>
		</div>
	</div>
</main>

<Footer />

<style>
	/* grid layout */
	Header {
		grid-area: h;
	}
	Nav {
		grid-area: n;
	}
	main {
		grid-area: m;
	}
	Footer {
		grid-area: f;
	}

	:global(body) {
		display: grid;
		grid:
			' h  ' auto
			' n  ' auto
			' m  ' auto
			' f  ' auto
			/ 1fr ;
	}

	/* global styles */
	:global(h1) {
		font-family: 'Petit Formal Script', cursive;
	}

	:global(h2) {
		font-family: 'Alegreya Sans SC', sans-serif;
	}

	:global(main) {
		font-family: 'Open Sans', sans-serif;
	}

	button {
		margin-right: 4em;
		margin-left: 4em;
		font-family: 'Alegreya Sans SC', sans-serif;
	}
</style>

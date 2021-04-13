<script>
	import Header from '$lib/Header.svelte';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
</script>
<section>
<Header />
<Nav />

<main class="hero is-large">
	<div class="hero-body has-bg-img">
		<div class="container has-text-centered">
			<a class="button is-large is-dark" href="design-heritage">Design Heritage</a>
			<a class="button is-large is-dark" href="visual-communication">Visual Communication</a>
		</div>
	</div>
</main>

<Footer />

</section>

<style>
	/* grid layout */
	:global(Header) {
		grid-area: h;
	}
	:global(Nav) {
		grid-area: n;
	}
	:global(main) {
		grid-area: m;
	}
	:global(Footer) {
		grid-area: f;
	}

	section {
		display: grid;
		grid:
			' h h ' auto
			' n n ' auto
			' m m ' auto
			' f f ' auto
			/ 1fr 1fr ;
		}

	/* global styles */
	:global(h1) {
		font-family: 'Petit Formal Script', cursive;
	}

	:global(h2) {
		font-family: 'Alegreya Sans SC', sans-serif;
	}

	:global(h3) {
		font-family: 'Alegreya Sans SC', sans-serif;
	}

	:global(main) {
		font-family: 'Open Sans', sans-serif;
	}

	a {
		margin-right: 4em;
		margin-left: 4em;
		font-family: 'Alegreya Sans SC', sans-serif;
	}
</style>

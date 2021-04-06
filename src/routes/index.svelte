<script>
	import Header from '$lib/Header.svelte';
	import Nav from '$lib/Nav.svelte';
</script>

<Header />
<Nav />

<main>

Design Heritage 
Visual Communication

</main>

<style>
	/* grid layout 
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

		display: grid;
		grid:
			' h   h   ' auto
			' n   n   ' auto
			' m   m   ' auto
			' f   f   ' auto
			/ 1fr 1fr;
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

</style>

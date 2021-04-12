<script>
	import Header from '$lib/Header.svelte';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<section>
	<Header />
	<Nav />

	<main>
		<h1 align="center">Design Heritage</h1>

		<h2 align="center">Homework Task</h2>

		<div class="box">
		<h3>SIZE: 1 x A3 Maximum</h3>
		<p>
			Pick one of the following Architects to create an A3 poster, read the assessment criteria:
		</p>

		<ol type="1">
			<li>Mies Van der Rohe</li>
			<li>Zaha Hadid</li>
			<li>Frank Gehery</li>
			<li>Le Cobuisier</li>
			<li>Frank Lloyd Wright</li>
			<li>Daniel Libeskind</li>
		</ol>

	</div>

	<div class="box">

		<h3>Creative Challenge...</h3>
		<p>
			Your presentation should reflect the style of the architect you have studied (shapes colours
			textures etc.).
		</p>

	</div>

	<div class="box">

		<h3>Answer...</h3>
		<p>
			What are the key features of their work?- aesthetic (looks) and functional (working) Include
			examples of their work and a little notes
		</p>

		<p>
			What context do they work within?- what cultural/historical/society or technological things
			influence their work? Do they have a design philosophy?- what do they try and do or think
			about design How long have they been designing? What are the main materials their buildings
			are made from? Are there any interesting facts you have found about them? Include a quote that
			they have said
		</p>

	</div>

	</main>

	<Footer />
</section>

<!-- style 1 -->
<style>
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

	section {
		background-color:#FFFCFF;
		display: grid;
		grid:
			' h h  h ' auto
			' n n  n ' auto
			' . m . ' auto
			' f f f ' auto
			/ 1fr 4fr 1fr
		
	}

	h1 {
		font-size: 2em;
	}

	h2 {
		font-size: 1em;
		padding-top: 1em;
		padding-bottom: 1em;
	}

	h3 {
		font-size: large;
		font-weight: bold;
		padding: 1em;
	}

	p {
		padding: 1em;
	}

	ol {
		padding: 2em;
	}

</style> 


<!-- style 2 

<style>
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

	section {
		background-color:#FFFCFF;
		display: grid;
		grid:
			' h h n n ' auto
			' . m m . ' auto
			' f f f f ' auto
			/ 1fr 2fr 2fr 1fr
		
	}

	h1 {
		font-size: 2em;
	}

	h2 {
		font-size: 1em;
		padding-top: 1em;
		padding-bottom: 1em;
	}

	h3 {
		font-size: large;
		font-weight: bold;
		padding: 1em;
	}

	p {
		padding: 1em;
	}

	ol {
		padding: 2em;
	}

</style>

-->

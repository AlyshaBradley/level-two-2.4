<script>
	import Header from '$lib/Header.svelte';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<section>
	<Header />
	<Nav />

	<main>
			<h1 align="center">Visual Communication</h1>

			<h2 align="center">Assessment Tasks</h2>

		<div class="box">
			<img
				src="static/images/image10.jpg"
				alt="Perspective"
				align="left"
				width="20%"
				height="auto"
			/>
			<h3>1.Perspective</h3>
			<p>
				Use the box examples on this sheet and create on your own page. Start by putting in a line
				for the horizon and the VP’s then the front side of each box. Then take the sides back to
				the vanishing points. If you get stuck draw the example. Place boxes in all different
				locations and make them different sizes.
			</p>
		</div>

		<div class="box">
			<img
				src="static/images/image8.jpg"
				alt="Perspective Bird Houses"
				align="left"
				width="20%"
				height="auto"
			/>
			<h3>2.Perspective Bird Houses</h3>
			<p>Draw the bird houses. Add shadows and textures</p>
		</div>

		<div class="box">
			<h3>3. Scale</h3>
			<p>
				explain or work out the following: What does 1:2 mean? Using 1:1 what size would you draw
				100mm at? Using 1:20 what size would you draw 100mm at? Using 1:50 what size would you draw
				100mm at? How do you work out scale? Explain this What unit of measurement must all
				dimensions be in?
			</p>
		</div>

		<div class="box">
			<img
				src="static/images/image9.jpg"
				alt="Architectural Symbols"
				align="left"
				width="20%"
				height="auto"
			/>
			<h3>4. Architectural Symbols</h3>
			<p>
				Draw up a plan view of a room that will show the following. Label each neatly in 3mm caps
				writing. You can adapt the drawing below or do your own. Think about colour and texture.
				Double doors 3 windows Walls A sink, a toilet and bath Seating Add a north symbol used for
				architecture Tiles Wooden flooring
			</p>
		</div>

		<div class="box">
			<img
				src="static/images/image11.png"
				alt="Architectural Plan"
				align="left"
				width="20%"
				height="auto"
			/>
			<h3>5. Architectural Plans, & Elevations</h3>
			<p>
				Draw an accurate to scale 1x floor plan, 3 elevations and 1xperspective of the cabin. You
				will be drawing at scale 1:50 for the elevations and floor plan. Add the wall thickness
				(walls are 100mm so will be drawn as 2mm thick ) Use the diagrams below to work out the
				correct measurements at scale 1:50 Once you have completed the plan view (floor plan)
				complete the 3 elevations and then move onto a perspective sketch.
			</p>

			<img
				src="static/images/image14.png"
				alt="Architectural Elevation"
				align="left"
				width="20%"
				height="auto"
			/>
		</div>
	</main>

	<Footer />
</section>

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
		background-color: #fffcff;
		display: grid;
		grid:
			' h h h ' auto
			' n n n ' auto
			' . m . ' auto
			' f f f ' auto
			/ 1fr 4fr 1fr;
	}

	h3 {
		font-size: large;
		font-weight: bold;
		padding: 1em;
	}

	.heading {
		font-size: large;
		text-align: center;
	}

	img {
		padding: 2em
	}

</style>

<svelte:head>
	<title>About</title>
</svelte:head>

<div class="outer">
	<div class="inner">
		<h1>Urban Inversion -- For People who Love and Hate Urban Life</h1>
		<div>
			<p>
				Urban Inversion was a "mayfly" as described by David Kipen in a poem he wrote in 2009 about
				the Los Angeles literary landscape of his youth. A mayfly is a short-lived, adult insect.
			</p>
			<p>
				Poetically speaking, that perfectly captures the character and lifespan of the former
				bookstore & community hang-out located on Santa Monica Boulevard in West Hollywood.
			</p>

			<p>
				Thanks to a neighborhood computer whiz, it offered on-line book purchases starting in 1995
				at the same time as or just ahead of the behemoth that we would all come to know as Amazon.
				Given its political bent, it was not without its controversy.
			</p>
		</div>
	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Marmelad&family=Pacifico&family=Special+Elite&family=Tangerine:wght@400;700&family=Ultra&display=swap');
	h1 {
color: teal;
border-radius: 1em;
padding: 1em;

		font-family: 'Special Elite', cursive;

	}

	p {
		font-family: 'Special Elite', sans-serif;
	}
	:global{
		--main-bg-color: rgba(160, 249, 192, 0.3);
	}
:root{
		--main-bg-color: rgba(160, 249, 192, 0.3);
	}

	.outer {
		font-size: 28px;
		width: 1000px;
		margin: 0 auto;
		background-color: lightolivegreen;
	}

	.inner {
		margin-left: 10px;
		background-color: var(--main-bg-color);
	}
</style>

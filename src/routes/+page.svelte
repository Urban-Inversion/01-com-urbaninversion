<!-- example for https://github.com/sveltejs/kit/discussions/5560#discussioncomment-3163837 -->
<script>
	let name = 'world';
	let theme = 'auto'
	
	const waterCss = {
		auto: 'https://cdn.jsdelivr.net/npm/water.css@2/out/water.css',
		dark: 'https://cdn.jsdelivr.net/npm/water.css@2/out/dark.css',
		light: 'https://cdn.jsdelivr.net/npm/water.css@2/out/light.css'
	}
</script>


<svelte:head>
<link href={waterCss[theme]} rel="stylesheet" />
<title>Urban Inversion</title>
</svelte:head>
<h1>Urban Inversion, 1994 - 1999</h1>

{#each Object.keys(waterCss) as t}
		<label>
			<input type='radio' value={t} bind:group={theme} />
			<span>{t}</span>			
		</label>
{/each}
<style>
                @import url('https://fonts.googleapis.com/css2?family=Marmelad&family=Pacifico&family=Special+Elite&family=Tangerine:wght@400;700&family=Ultra&display=swap');
                h1 {
                        font-family: 'Special Elite', cursive;
                }

* {
  box-sizing: border-box;
}


.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* create four equal columns that sits next to each other */
.column {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}
</style>


<div class="row">
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0001(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0001.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0002.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0003.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0004(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0004.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0005(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0005.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0006(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0006.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0007(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0007.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0008(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0008.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0009(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0009.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0010(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0010.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0011(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0011.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0012(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0012.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0013(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0013.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0014(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0014.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0015(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0015.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0016(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0017.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0018.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0023.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0024.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0016.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0002(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
    <div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/Host CP.webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
<div class="column"><img src="https://storage.googleapis.com/urban-inversion/a-WEBP/IMG_0003(1).webp" alt="some description" onclick="window.open(this.src, '_blank')"></div>
</div>

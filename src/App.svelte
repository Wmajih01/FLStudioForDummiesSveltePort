<script>
</script>

<svelte:head>
	<title>FL Studio for dummies</title>
	<html lang="en" />
</svelte:head>

<body style="background-image: url(resources/Mosaic.jpg);" alt="Background">
	<div id="table">
		<form action="#TopScreen" method="GET">
			<input
				type="image"
				src="resources/TableofContentsButtons/Btn0.jpg"
				alt="TableOfContents"
			/>
			<form action="#HowDoIGetFLStudio" method="GET">
				<input
					type="image"
					src="resources/TableofContentsButtons/Btn1.jpg"
					alt="What is FL Studio?"
				/>
			</form>
			<form action="#Startup" method="GET">
				<input
					type="image"
					src="resources/TableofContentsButtons/Btn2.jpg"
					alt="Startup"
				/>
			</form>
		</form>
	</div>
	<div id="main">
		<p style="text-align: center">
			<img
				src="resources/BigFruit.jpg"
				alt="FruityLogo"
				width="238"
				height="338"
			/>
		</p>
		<h1><a id="TopScreen">A MEDIOCRE STARTERGUIDE FOR FRUITYLOOPS </a></h1>
		<p>
			Say, you want to make som music, right. You know your basic
			melodies, your Dur and Mol chords, but you want to take a step
			further. You want to digitalize your tunes, but are unsure on how to
			pull off such an unimaginable feat. This guide was specifically made
			for people like you who have no idea what a DAW is yet want to
			arrange something. That's why I'll be cutting the BS and get
			straight to the point when I'm trying to make a point, and we're
			going to use FL Studio to achieve this - the music making I mean.
		</p>
		<h2><a id="HowDoIGetFLStudio">How do I get FL Studio? </a></h2>
		<p>
			FL Studio is free, and can be downloaded through Image-Line's
			website. Naturally, you couldn't be arsed to go get it yourself, so
			I've prepared a link for you by myself right <a
				href="https://www.image-line.com/downloads/flstudiodownload.html?__cf_chl_jschl_tk__=42694613f2f40e41698683c9fe67768dabc7bd5f-1591018275-0-AWURhZV2SjqT-tvN88MCAmO4sqYMsqAgLO1YJKn3q5i-wFoGzhJePYL5idlDUQjJkk1nfsxlgAt8hfsx9W6UfIlQyK1VpcCK5_9RflIy1ScKVpdY6Zw-myqd6l_cSDZ4HExQsH60NfkgacHld-SJQ3Z_HaBPg6eBx25OYL-lDZ65kSjgAlSscm8o0jmIY8Er_tfnrgrEfSiAfbC8ZbJgtg_37AUDcVeBWw2Lbt7SDIDaYGkjAZ0aKjBms1YZrfmQPMQLEsmjVs8pkbV2jvMIX5Ug1FNsW6uUmspVkwKdQ9bUij3oZle6lz2MbK2Qkoq7rA"
				target="_blank">here.</a
			> Keep in mind that you can't load up songs with the free version, however
			that should be the least of your concerns regarding the fact that you
			don't even know how to use this DAW yet!
		</p>
		<h2><a id="Startup">Startup </a></h2>
		<p>
			Make sure you install the DAW with the preffered attributes. When
			you start FL Studio up, you should get something like this:
		</p>
		<p>
			<img
				src="resources/GuideScreens/FLStudio.jpg"
				alt="The Main Menu Screen"
			/>
		</p>
	</div>
</body>

<style>
	body {
		display: flex;
	}
	#table {
		display: flex;
		flex-direction: column;
	}
	#main {
		width: 1550;
	}
	h1 {
		font-family: francois_oneregular;
		font-size: 40;
		text-align: center;
		text-shadow: 1px 2px #000000;
		margin: 100 auto;
		color: rgb(255, 240, 230);
	}
	h2 {
		font-family: francois_oneregular;
		text-shadow: 1px 2px #000000;
		font-size: 40;
		text-align: center;
		margin: 0 auto;
		color: rgb(255, 240, 230);
	}
	p {
		font-size: 30px;
		font-family: cuprumregular;
		width: 1000px;
		text-align: left;
		margin: 5 auto;
		color: rgb(255, 240, 230);
	}
	form {
		margin-bottom: 0px;
	}
	@font-face {
		font-family: "Cuprumregular";
		src: url("/fonts/cuprumregular/cuprum-webfont.woff") format("woff");
	}
	@font-face {
		font-family: "francois_oneregular";
		src: url("/fonts/francoisone/francoisone-webfont.woff") format("woff");
	}
</style>

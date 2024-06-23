<style>html
{
	padding: 0 1em;
	font-family: Calibri, sans-serif;
}

body
{
	margin: auto;
	max-width: 42em;
}

img
{
	max-width: 100%;
}

.image-left, .image-right
{
	margin: 1em 0;
}

@media (min-width: 20em)
{
	.image-left, .image-right
	{
		display: flex;
		align-items: center;
	}

	.image-left img
	{
		margin-right: 1em;
		float: left; /* fallback */
	}

	.image-right img
	{
		order: 1;
		margin-left: 1em;
		float: right; /* fallback */
	}
	
	/* clearfix for fallback */
	.image-left::after,
	.image-right::after
	{
		content: "";
  	display: block;
		clear: both;
	}
}

@media (min-width: 30em)
{
	.image-left img, .image-right img
	{
		flex-shrink: 0;
	}
}</style>
<div class="image-right">
	<img src="https://static.wikia.nocookie.net/dragonball/images/b/b2/Krilin_DB_Artwork.png/revision/latest?cb=20161216144931&path-prefix=es">
	<div>
		<p>The Human Rights Logo has its origin in the international “Logo for Human Rights” initiative, which was started in 2010. Its goal was to create an internationally recognized logo to support the global human rights movement. The winning logo was created by Predrag Stakić from Serbia.</p>
		<footer>(from Wikipedia)</footer>
	</div>
</div>


<!--
**txaberOcio/txaberOcio** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

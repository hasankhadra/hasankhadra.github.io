<script lang="ts">
	import { base } from '$app/paths';
</script>

<header>
	<h1>Hasan Khadra Portfolio</h1>

	<h2>Blockchain and Frontend Developer</h2>
	<h2>Pianist and guitarist</h2>
	<nav class="navigation">
		<a href="{base}/">Home Page</a>
		<a href="{base}/about">About me</a>
		<a href="{base}/randomQuotes">Random Quotes</a>
	</nav>
</header>

<style>
	header {
		background-color: #e3dcc2;
		padding: 1em;
		text-align: center;
	}

	.navigation {
		padding: 1em;
		text-align: center;
		font-size: x-large;
	}

	.navigation > a {
		color: #51513d;
		text-decoration: double;
		margin: auto 10%;
	}
</style>

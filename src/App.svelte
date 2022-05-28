<script lang="ts">
	import Header from './components/Header.svelte';
	import "./app.css";

	export let name: string;
</script>

<main>
	<Header />
	<div class="content">
		<h1>Hello {name}!</h1>
		<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	</div>
</main>

<style>
	:global(body) {
		/* this will apply to <body> */
		margin: 0;
	}
	main {
		text-align: center;
	}
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	.content{
		margin: 3rem 0;
	}
</style>
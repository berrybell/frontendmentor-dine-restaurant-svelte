<script>
	export let name;
</script>

<svelte:head>
	<meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">

  <title>Frontend Mentor | Dine Website Challenge</title>
</svelte:head>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
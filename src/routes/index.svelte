<script>
	import NavComponent from '$lib/layout/NavComponent.svelte';
	import Button from '$lib/button/Button.svelte';
	import About from './about.svelte';
</script>

<h1 class="text-3xl font-bold underline">Hello world!</h1>
<button class="btn">Button</button>
<h1>1 Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<NavComponent />
<Button />
<About />

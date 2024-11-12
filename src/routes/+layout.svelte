<script lang="ts">
	import '../app.postcss';

	let { children } = $props();
</script>

<div class="app bg-primary-500">
	<main>
		{@render children()}
	</main>

	<footer>
		<p>
			visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to learn about SvelteKit
		</p>
	</footer>
</div>

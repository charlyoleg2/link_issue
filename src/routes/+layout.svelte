<script lang="ts">
	import { base } from '$app/paths';
</script>

<h1>Testing the bug</h1>
<nav>
	<!--a href={`${base}/`}>home</a-->
	<a href="{base}">home</a>
</nav>
<main>
	<slot />
</main>

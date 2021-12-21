<script lang="ts">
	import Footer from './Footer.svelte';
	import Header from './Header.svelte';
</script>

<Header />
<main class="layout px-4 py-8">
	<slot />
</main>
<Footer />

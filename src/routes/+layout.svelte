<script>
	import '../app.pcss';
	import Footer from '../components/Footer.svelte';
	import Header from '../components/Header.svelte';
</script>

<div class="flex min-h-screen flex-col">
	<div class="sticky left-0 top-0 z-50 w-full bg-white">
		<Header />
	</div>
	<div class="flex-1">
		<slot />
	</div>
</div>
<Footer />

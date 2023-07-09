<script>
	import Footer from '$lib/components/Footer.svelte';
	import '../app.css';
	import Navbar from '../lib/components/Navbar.svelte';
</script>

<Navbar />
<slot />
<Footer />

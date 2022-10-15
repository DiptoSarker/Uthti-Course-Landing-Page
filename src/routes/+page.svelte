<script>
	import Nav from '../Components/CourseTitleHeaderNav.svelte';
	import '../app.css';
	import Body from '../Components/Body.svelte';
	import CourseSectionNav from '../Components/CourseSectionNav.svelte';
	import MainNavBar from '../Components/MainNavBar.svelte';
	import Footer from '../Components/Footer.svelte';
</script>

<main>
	<div class="main"><MainNavBar /></div>
	<div class="optional">
		<Nav />
		<!-- <CourseSectionNav /> -->
		<Body />
		<Footer />
	</div>
</main>

<style>
	.optional {
		position: relative;
	}

	.main {
		position: absolute;
		top: 0;
		width: 100%;
		z-index: 3333;
	}
</style>

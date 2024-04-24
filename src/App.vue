<script>
	// Import components
	import PageHeader from './components/PageHeader.vue';
	import PageHero from './components/PageHero.vue';
    import PageMain from './components/PageMain.vue';
	import PageFooter from './components/PageFooter.vue';
	export default{
		// Name components
		components: {
			PageHeader,
			PageHero,
            PageMain,
			PageFooter
		}
	}
</script>

<template>
	<header> 
		<PageHeader></PageHeader>
	</header>
	<main>
		<PageHero></PageHero>
		<PageMain></PageMain>
	</main>
	<footer>
		<PageFooter></PageFooter>
	</footer>
</template>

<style scoped lang="scss">
@use './style/generic' as *;
</style>

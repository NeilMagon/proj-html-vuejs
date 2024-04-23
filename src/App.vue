<script>
	import PageHeader from './components/PageHeader.vue';
    import PageMain from './components/PageMain.vue';
	import PageFooter from './components/PageFooter.vue';
	export default{
		components: {
			PageHeader,
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
		<PageMain></PageMain>
	</main>
	<footer>
		<PageFooter></PageFooter>
	</footer>
</template>

<style scoped lang="scss">
@use './style/generic' as *;
</style>

<script>
    import PageHero from './PageHero.vue';
	export default {
        name: 'PageMain',
        components: {
			PageHero,
		}
    }
</script>

<template>
    <PageHero></PageHero>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

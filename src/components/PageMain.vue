<script>
    import PageHero from './PageHero.vue';
    import StudentInfo from './StudentInfo.vue';
	export default {
        name: 'PageMain',
        components: {
			PageHero,
            StudentInfo,
		}
    }
</script>

<template>
    <PageHero></PageHero>
    <StudentInfo></StudentInfo>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

<script>
    import PageHero from './PageHero.vue';
    import StudentInfo from './StudentInfo.vue';
    import EventsUniversity from './EventsUniversity.vue';
	export default {
        name: 'PageMain',
        components: {
			PageHero,
            StudentInfo,
            EventsUniversity,
		}
    }
</script>

<template>
    <PageHero></PageHero>
    <StudentInfo></StudentInfo>
    <EventsUniversity></EventsUniversity>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

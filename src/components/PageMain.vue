<script>
    import PageHero from './PageHero.vue';
    import StudentInfo from './StudentInfo.vue';
    import EventsUniversity from './EventsUniversity.vue';
    import CoursesInfo from './CoursesInfo.vue';
	export default {
        name: 'PageMain',
        components: {
			PageHero,
            StudentInfo,
            EventsUniversity,
            CoursesInfo
		}
    }
</script>

<template>
    <PageHero></PageHero>
    <StudentInfo></StudentInfo>
    <EventsUniversity></EventsUniversity>
    <CoursesInfo></CoursesInfo>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

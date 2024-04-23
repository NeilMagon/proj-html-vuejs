<script>
    import StudentInfo from './StudentInfo.vue';
    import EventsUniversity from './EventsUniversity.vue';
    import CoursesInfo from './CoursesInfo.vue';
	export default {
        name: 'PageMain',
        components: {
            StudentInfo,
            EventsUniversity,
            CoursesInfo
		}
    }
</script>

<template>
    <StudentInfo></StudentInfo>
    <EventsUniversity></EventsUniversity>
    <CoursesInfo></CoursesInfo>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

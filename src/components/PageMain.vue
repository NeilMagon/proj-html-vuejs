<script>
    // Import components
    import StudentInfo from './StudentInfo.vue';
    import EventsUniversity from './EventsUniversity.vue';
    import CoursesInfo from './CoursesInfo.vue';
	export default {
        name: 'PageMain',
        // Name components
        components: {
            StudentInfo,
            EventsUniversity,
            CoursesInfo
		}
    }
</script>

<template>
    <!-- Top-main -->
    <StudentInfo></StudentInfo>
    <!-- Central-main -->
    <EventsUniversity></EventsUniversity>
    <!-- Bottom-main -->
    <CoursesInfo></CoursesInfo>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

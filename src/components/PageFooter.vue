<script>
    // Import components
    import FooterPartners from './FooterPartners.vue';
    import FooterInfo from './FooterInfo.vue';
	export default {
        name: 'PageFooter',
        // Name components
        components: {
            FooterPartners,
            FooterInfo
        },
    }
</script>

<template>
    <!-- Footer-top -->
    <FooterPartners></FooterPartners>
    <!-- Footer-bottom -->
    <FooterInfo></FooterInfo>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

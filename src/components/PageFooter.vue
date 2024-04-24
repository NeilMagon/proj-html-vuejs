<script>
    import FooterPartners from './FooterPartners.vue';
    import FooterInfo from './FooterInfo.vue';
	export default {
        name: 'PageFooter',
        components: {
            FooterPartners,
            FooterInfo
        },
    }
</script>

<template>
    <FooterPartners></FooterPartners>
    <FooterInfo></FooterInfo>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

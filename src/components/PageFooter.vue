<script>
    import FooterPartners from './FooterPartners.vue';
	export default {
        name: 'PageFooter',
        components: {
            FooterPartners,
        }
    }
</script>

<template>
    <FooterPartners></FooterPartners>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
</style>

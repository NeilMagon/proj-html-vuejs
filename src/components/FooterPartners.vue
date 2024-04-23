<script>
	export default {
        name: 'FooterPartners',
    }
</script>

<template>
    <section class="ms-bg py-5">
        <div class="container">
            <div class="d-flex justify-content-between">
                <div class="text-white">
                    <h1>Subscribe Now to Our Newsletter !</h1>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    section{
        &.ms-bg{
            background-color: $brand-primary;
        }
        h1{
            font-weight: bold;
        }
    }
</style>

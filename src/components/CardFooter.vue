<script>
	export default {
        name: 'CardFooter',
           // Props
        props: {
            footerInfo: Object,
        },
    }
</script>

<template>
    <!-- List-info-footer -->
	<div class="col-2 text-white">
        <h5>{{footerInfo.title}}</h5>
        <ul class="navbar-nav pt-3">
            <li v-for="link in footerInfo.link" :key="link" class="nav-item">
                <a class="nav-link" href="#">{{ link }}</a>
            </li>
        </ul>
    </div>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    a{
        font-size: 14px
    }
</style>
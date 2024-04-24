<script>
	export default {
        name: 'CardImg',
        // Props
        props: {
            cardinfo: Object,
        },
        // Funzione per generare immagini
        methods: {
            generateImage(name) {
                return new URL(`${name}`, import.meta.url).href
            }
        }
    }
</script>

<template>
    <!-- Img-card -->
    <div class="ms-img">
        <img :src="generateImage(cardinfo.url)" alt="">
    </div>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    img{
        width: 100%;
        height: 100%;
    }
    .ms-img{
           height: 60px;
        }
</style>
<script>
    import CardImg from './CardImg.vue';
	export default {
        name: 'FooterPartners',
        components: {
            CardImg
        },
        data() {
            return {
                // Array di oggetti contenente l'url delle immagini
                infos: [
                    {
                        url:"../assets/img/img/partner-2.png"
                    },
                    {
                        url:"../assets/img/img/partner-3.png"
                    },
                    {
                        url:"../assets/img/img/partner-4.png"
                    },
                    {
                        url:"../assets/img/img/partner-5.png"
                    },
                    {
                        url:"../assets/img/img/partner-6.png"
                    },
                    {
                        url:"../assets/img/img/partner-8.png"
                    },
                    {
                        url:"../assets/img/img/partner-1.png"
                    },
                    {
                        url:"../assets/img/img/partner-7.png"
                    },
                ]
            }
        },
    }
</script>

<template>
    <section class="ms-bg py-5">
        <div class="container">
            <div class="d-flex justify-content-between">
                <!-- Form -->
                <div class="text-white">
                    <h1>Subscribe Now to Our Newsletter !</h1>
                </div>
                <!-- Search-bar -->
                <div class="input-group position-relative w-40">
                    <input type="email" class="form-control rounded-5" placeholder="Email Address..." aria-label="Indirizzo email" aria-describedby="basic-addon2">
                    <div class="h-100 position-absolute end-0 ">
                        <button class="h-100 ms-circle-btn text-white btn rounded-circle px-4" type="button" id="basic-addon2">
                            <i class="fa-solid fa-paper-plane"></i>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="py-5">
        <!-- Img-partners -->
        <div class="container text-center">
            <h1>Partners</h1>
            <p class="my-5">
                Leverage agile frameworks to provide a robust synopsis for hight level <br>
                overviews. Iterative approaches to corporate strategy.
            </p>
            <div class="d-flex justify-content-center gap-4">
                <!-- Ciclo l'array per passarlo al figlio tramite props -->
                <CardImg v-for="info in infos" :cardinfo="info"></CardImg>
            </div>
        </div>
        <div class="ms-image">
            <img src="../assets/img/img/background-wave3.png" alt="">
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    img{
                width: 100%; 
                height: 100%;
            }
    section{
        &.ms-bg{
            background-color: $brand-primary;
        }
        h1{
            font-weight: bold;
        }
        .w-40{
            width: 40%;
            .ms-circle-btn{
                background-color: $brand-secondary;
            }
        }
        .ms-image{
            width: 100%;
            height: 200px;
        }
    }
</style>

<script>
    import CardFooter from './CardFooter.vue';
	export default {
        name: 'FooterInfo',
        components: {
            CardFooter,
        },
        data() {
            return {
                infos: [
                    {
                        "title": "Get EduPrime",
                        "link": ["Request a website", "Browse Themes", "Payment options", "Support System", "Checkout", "Purchase Theme"]
                    },
                    {
                        "title": "Networking",
                        "link": ["Purchase Theme", "Our Benefits", "Our Team", "Our Services", "Other Products", "My account"]
                    },
                ]
            }
        },
    }
</script>

<template>
    <section class="py-5 ms-bg">
        <div class="container mt-5">
            <div class="row pt-5">
                <div class="col-4">
                    <div class="ms-img pb-3">
                        <img src="../assets/img/img/theme_eduprime_logo.png" alt="logo-eduprime">
                    </div>
                    <p class="py-4 text-white">
                        EduPrime is the most versatile WordPress theme for educational purpose, 
                        showcasing universities, courses, secondary schools etc.
                    </p>
                    <button class="btn rounded-circle ms-small-btn text-white"><i class="fa-brands fa-facebook-f"></i></button>
                    <button class="btn mx-3 rounded-circle ms-small-btn text-white"><i class="fa-brands fa-twitter"></i></button>
                    <button class="btn rounded-circle ms-small-btn text-white"><i class="fa-brands fa-instagram"></i></button>
                </div>
                <CardFooter v-for="info, index in infos" :footerInfo="info"></CardFooter>
                <div class="col-4 text-end">
                    <div class="input-group position-relative mb-5">
                        <input type="email" class="form-control rounded-5 py-3" placeholder="Email Address..." aria-label="Indirizzo email" aria-describedby="basic-addon2">
                        <div class="position-absolute end-0 ">
                            <button class="ms-big-circle-btn text-white btn rounded-circle p-3" type="button" id="basic-addon2">
                                <i class="fa-solid fa-magnifying-glass"></i>
                            </button>
                        </div>
                    </div>
                    <h6 class="text-white">Search categories</h6>
                    <div class="d-flex flex-wrap gap-3 justify-content-end py-4 text-white">
                        <span class="p-2 rounded-4">ECONOMY</span>
                        <span class="p-2 rounded-4">DESIGN</span>
                        <span class="p-2 rounded-4">COACHING</span>
                        <span class="p-2 rounded-4">BUSINESS</span>
                        <span class="p-2 rounded-4">MEDICINE</span>
                        <span class="p-2 rounded-4">LAW</span>
                        <span class="p-2 rounded-4">FITNESS</span>
                    </div>
                    <p class="ms-p">ModelTheme. All rights reserved.</p>
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
        .ms-img{
            width: 250px;
            img{
                width: 100%;
            }
        }
        ul li{
            list-style: none;
        }
        .ms-small-btn{
            border-color: $brand-secondary;
        }
        .ms-big-circle-btn{
            background-color: $brand-secondary;
        }
        h5 h6{
            font-weight: bold;
        }
        .ms-p{
            color: $brand-secondary;
        }
        span{
            font-size: 10px;
            border: 1px solid;
        }
    }
</style>
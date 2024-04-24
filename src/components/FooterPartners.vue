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
        <div class="container text-center">
            <h1>Partners</h1>
            <p class="my-5">
                Leverage agile frameworks to provide a robust synopsis for hight level <br>
                overviews. Iterative approaches to corporate strategy.
            </p>
            <div class="d-flex ms-img">
                <div class="ms-img">
                    <img src="../assets/img/img/partner-2.png" alt="">
                </div>
            </div>
        </div>
        <div class="ms-image">
            <img src="../assets/img/img/background-wave3.png" alt="">
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
        .w-40{
            width: 40%;
            .ms-circle-btn{
                background-color: $brand-secondary;
            }
        }
        .ms-image{
            width: 100%;
            height: 200px;
            img{
                width: 100%; 
                height: 100%;
            }
        }
    }
</style>

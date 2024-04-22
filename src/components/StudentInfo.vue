<script>
	export default {
        name: 'StudentInfo',
    }
</script>

<template>
    <section class="p-5">
        <div class="container">
            <div class="row gx-5">
                <div class="col">
                    <div class="ms-img">
                        <img src="../assets/img/img/Books-icon.png" alt="">
                    </div>
                    <h1 class="mt-3">Thousands of courses for any type of student</h1>
                    <p class="my-5">At EduPrime, it doesn't matter what domain you wish to pursue a career in. Here you can finda course that
                        satisfies your needs within a click away and applies for a course in a matter of minutes. EduPrime is ranked
                        as the most versatile university in the world, thanks to the number of courses it provides.
                    </p>
                    <button class="ms-button btn px-4 py-3 text-white">Browse through courses</button>
                </div>
                <div class="col">
                    <div class="">
                        <img src="../assets/img/img/Graduation-Illustration.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    section{
        background-image: url('../assets/img/img/home-background.png');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        .ms-img{
            height: 40px;
        }
        img{
                height: 100%;
                width: 100%;
                object-fit: contain;
                object-position: left;
            }
        h1{
            font-weight: bold;  
        }
        .ms-button{
            background-color: $brand-secondary;
            border-radius: 30px;
            font-weight: bold;
        }
    }
</style>
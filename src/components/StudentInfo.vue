<script>
	export default {
        name: 'StudentInfo',
    }
</script>

<template>
    <section class="p-5 ms-bg-img">
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
    <section>
        <div class="text-center ms-b-border">
            <h1 class="pt-5">Faculties available at EduPrime</h1>
            <p class="py-3">A single university with a load of courses, tailored <br> to satisfy any student's needs.</p>
            <div class="shadow">
                <div class="container">
                    <div class="row">
                        <div class="col py-5 ms-border text-center ms-back">
                            <img class="ms-image immagine-colorata" src="../assets/img/img/Gavel-v2.png" alt="Low Faculty">
                            <p class="pt-3 text-white">Low Faculty</p>
                        </div>
                        <div class="col py-5 ms-border text-center">
                            <img class="ms-image" src="../assets/img/img/Coins-tabs-v2.png" alt="Low Faculty">
                            <p class="pt-3">Economy</p>
                        </div>
                        <div class="col py-5 ms-border text-center">
                            <img class="ms-image" src="../assets/img/img/Medicine-tabs-v2.png" alt="Low Faculty">
                            <p class="pt-3">Medicine</p>
                        </div>
                        <div class="col py-5 ms-border text-center">
                            <img class="ms-image" src="../assets/img/img/Computer-tabs-v2.png" alt="Low Faculty">
                            <p class="pt-3">Computer Science</p>
                        </div>
                        <div class="col py-5 ms-border text-center">
                            <img class="ms-image" src="../assets/img/img/Palette-tabs-v2.png" alt="Low Faculty">
                            <p class="pt-3">Graphic Design</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container">
                <div class="row mt-5 gx-5">
                    <div class="col my-5">
                        <div>
                            <img src="../assets/img/img/Gavel-Illustration-e1556884768193.png" alt="">
                        </div>
                    </div>
                    <div class="col text-start my-5">
                        <h1 class="mt-3">Law Faculty</h1>
                        <p class="my-5">
                            Learning from world-leading academics and practitioners, you'll not only receive an 
                            outstanding grounding in the theory of law, but you will be able to understand how those principles are applied in practice
                            through a range of student-led activities and competitions
                        </p>
                        <button class="px-5 py-3 btn ms-btn text-white">Read More</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    .ms-bg-img{
        background-image: url('../assets/img/img/home-background.png');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        .ms-img{
            height: 40px;
        }
        .ms-button{
            background-color: $brand-secondary;
            border-radius: 30px;
            font-weight: bold;
        }
    img{
            height: 100%;
            width: 100%;
            object-fit: contain;
            object-position: left;
        }
    }
    h1{
        font-weight: bold;  
        }
    .ms-border{
        border: 1px solid #ECECEE;
        cursor: pointer;
        .ms-image{
            width: 100px;
        }
        &.ms-back{
            background-color: $brand-primary;
        }
        .immagine-colorata{
            filter: saturate(0%);
        }
        p{
            color : $brand-primary;
            font-weight: bold;
        }
    }
    .ms-btn{
        background-color: $brand-primary;
        border-radius: 30px;
        font-weight: bold;
    }
</style>
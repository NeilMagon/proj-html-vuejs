<script>
	export default {
        name: 'CoursesInfo',
    }
</script>

<template>
    <section class="pb-5">
        <div class="container">
            <h1>Latest Courses</h1>
            <div class="row gap-5 my-5">
                <div class="col shadow text-center py-5 position-relative">
                    <img class="ms-img" src="../assets/img/img/Decisions-icon.png" alt="">
                    <h5 class="py-2">Make Better Decisions</h5>
                    <p><i class="fa-solid fa-user"></i> <span>Teacher:</span> James Collins</p>
                    <p><i class="fa-solid fa-money-bill-1-wave"></i> <span>Price:</span> $21.00</p>
                    <div class="position-absolute top-100 start-50 translate-middle">
                        <button class="py-2 px-4 text-white btn rounded-5 ms-button"><i class="fa-solid fa-eye"></i> View Course</button>
                    </div>
                </div>
                <div class="col shadow text-center py-5 position-relative">
                    <img class="ms-img" src="../assets/img/img/Speaker-icon.png" alt="">
                    <h5 class="py-2">Make Better Decisions</h5>
                    <p><i class="fa-solid fa-user"></i> <span>Teacher:</span> James Collins</p>
                    <p><i class="fa-solid fa-money-bill-1-wave"></i> <span>Price:</span> Free</p>
                    <div class="position-absolute top-100 start-50 translate-middle">
                        <button class="py-2 px-4 text-white btn rounded-5 ms-button"><i class="fa-solid fa-eye"></i> View Course</button>
                    </div>
                </div>
                <div class="col shadow text-center py-5 position-relative">
                    <img class="ms-img" src="../assets/img/img/Network-icon.png" alt="">
                    <h5 class="py-2">Make Better Decisions</h5>
                    <p><i class="fa-solid fa-user"></i> <span>Teacher:</span> James Collins</p>
                    <p><i class="fa-solid fa-money-bill-1-wave"></i> <span>Price:</span> Free</p>
                    <div class="position-absolute top-100 start-50 translate-middle">
                        <button class="py-2 px-4 text-white btn rounded-5 ms-button"><i class="fa-solid fa-eye"></i> View Course</button>
                    </div>
                </div>
                <div class="col shadow text-center py-5 position-relative">
                    <img class="ms-img" src="../assets/img/img/Brand-icon.png" alt="">
                    <h5 class="py-2">Make Better Decisions</h5>
                    <p><i class="fa-solid fa-user"></i> <span>Teacher:</span> James Collins</p>
                    <p><i class="fa-solid fa-money-bill-1-wave"></i> <span>Price:</span> Free</p>
                    <div class="position-absolute top-100 start-50 translate-middle">
                        <button class="py-2 px-4 text-white btn rounded-5 ms-button"><i class="fa-solid fa-eye"></i> View Course</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="p-5">
        <div class="container">
            <div class="row gx-5">
                <div class="col">
                    <div class="ms-image">
                        <img src="../assets/img/img/Exam-icon.png" alt="">
                    </div>
                    <h1 class="mt-3">The most efficient examination method</h1>
                    <p class="my-5">
                        EduPrime has gathered teachers from around the globe to braibstorm in order to facilitate
                        the evaluation of our students. Every teacher from our university has an 
                        influence on how students are evaluated at her/his subject.
                    </p>
                    <button class="ms-button btn rounded-5 px-4 py-3 text-white">Discover the Method</button>
                </div>
                <div class="col">
                    <div>
                        <img src="../assets/img/img/Exam-Illustration.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="pt-5">
        <div class="container">
            <div class="row gx-5">
                <div class="col">
                    <div>
                        <img src="../assets/img/img/Girl-Illustration.png" alt="">
                    </div>
                </div>
                <div class="col">
                    <div class="ms-image">
                        <img src="../assets/img/img/Exam-icon-1.png" alt="">
                    </div>
                    <h1 class="mt-3">The most efficient examination method</h1>
                    <p class="my-5">
                        EduPrime has gathered teachers from around the globe to braibstorm in order to facilitate
                        the evaluation of our students. Every teacher from our university has an 
                        influence on how students are evaluated at her/his subject.
                    </p>
                    <button class="ms-button btn rounded-5 px-4 py-3 text-white">Discover the Method</button>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    section{
        .ms-img{
            width: 100px;
        }
        h1{
            font-weight: bold;
        }
        p{
            span, i{
                color: grey;
            }
        }
        .ms-button{
            background-color: $brand-primary;
            font-weight: bold;
            font-size: 14px;
            i{
                font-size: 10px;
            }
        }
        .ms-image{
            width: 50px;
        }
    }
    img{
        width: 100%;
    }
</style>

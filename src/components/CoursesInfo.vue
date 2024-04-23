<script>
	export default {
        name: 'CoursesInfo',
    }
</script>

<template>
    <section>
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
    }
</style>

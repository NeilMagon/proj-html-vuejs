<script>
	export default {
        name: 'PageHero',
    }
</script>

<template>
    <section class="position-relative d-flex">
        <div class="position-absolute top-50 start-0 translate-middle-y">
            <ul class="text-white rounded p-2">
                <li><a href="#"><i class="fa-solid fa-cart-shopping"></i></a></li>
                <li><a href="#"><i class="fa-solid fa-book-open"></i></a></li>
                <li><a href="#"><i class="fa-solid fa-spinner"></i></a></li>
            </ul>
        </div>
        <div class="text-center ms-container text-white p-5">
            <h1>Key to your succes</h1>
            <p class="my-5">EduPrime is the most versatile WordPress theme for educational purpose, showcasing universities, courses, secondary schools etc.</p>
            <button class="btn ms-button text-white px-4 py-3 mx-4"><i class="fa-solid fa-magnifying-glass"></i> Search courses</button>
            <button class="btn ms-button bg-white ms-color px-5 py-3"><i class="fa-solid fa-user-plus"></i> Apply for university</button>
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    section{
        background-image: url('../assets/img/hero.png');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        height: 500px;
        a{
            color: $brand-tertiary;
        }
    }
    ul{
        background-color: $brand-secondary;
        padding-left: 0;
        list-style: none;
    } 
    .ms-container{
        width: 650px;
        margin: auto;
        h1{
            font-size: 50px;
            font-weight: bold;
        }
        .ms-button{
            background-color: $brand-secondary;
            border-radius: 30px;
            font-weight: bold;
            &.ms-color{
                color: $brand-primary;
            }
        }
        i{
            font-size: 12px;
        }
    }
</style>

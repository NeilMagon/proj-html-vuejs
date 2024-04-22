<script>
	export default {
        name: 'PageHeader',
    }
</script>

<template>
    <nav class="navbar">
        <div class="container-fluid px-5 pt-4">
            <div class="ms-img">
                <img src="../assets/img/img/theme_eduprime_logo.png" alt="logo-eduprime">
            </div>
            <div class="d-flex align-items-center justify-content-between gap-3" id="navbarNav">
                <ul class="navbar-nav flex-row gap-4">
                    <li class="nav-item">
                        <a class="nav-link ms-active" aria-current="page" href="#">Home <i class="fa-solid fa-caret-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Courses <i class="fa-solid fa-caret-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link " href="#">News <i class="fa-solid fa-caret-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link " href="#">Pages <i class="fa-solid fa-caret-down"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link " href="#">Contact</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link " href="#">Purchase</a>
                    </li>
                </ul>
                <button class="btn ms-button text-white px-5 py-3">VIEW COURSES</button>
            </div>
        </div>
    </nav>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    nav{
        background-color: $brand-primary;
        font-weight: bold;
        i{
            font-size: 10px;
        }
        img{
            width: 12.5rem;
        }
        a{
            color: $brand-tertiary;
            &.ms-active{
                color: $brand-secondary;
            }
        }
        .ms-button{
            background-color: $brand-secondary;
            border-radius: 30px;
            font-weight: bold;
        }
    }
</style>

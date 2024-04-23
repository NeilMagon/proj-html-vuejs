<script>
	export default {
        name: 'EventsUniversity',
    }
</script>

<template>
    <div class="ms-img">
        <img src="../assets/img/svg/svg-0.svg" alt="">
    </div>
    <section class="text-center">
        <div class="container py-5">
            <img class="ms-image" src="../assets/img/img/Clock-and-Bell.png" alt="">
            <h1 class="my-4 text-white ms-text-bg">University Year</h1>
            <div class="row py-5">
                <div class="col col-4 text-white offset-3 text-center">
                    <h5>Demo Classes</h5>
                    <p>
                        In the first week, students try to accommodate with the
                        teaching style and choose their opzional courses.
                    </p>
                </div>
                <div class="col col-4 text-white text-center">
                    <h5>Graduation Day</h5>
                    <p>
                        ON the day of graduation, all students gather for the ceremory 
                        and then network and party among others.
                    </p>
                </div>
            </div>
            <img src="../assets/img/img/Timeline-Item.png" alt="">
            <div class="row">
                <div class="col col-4 text-white offset-1 text-center">
                    <h5>Orientation</h5>
                    <p>
                       First day of the university year, all students gather for the 
                       opening ceremory and then network with others.
                    </p>
                </div>
                <div class="col col-4 text-white text-center">
                    <h5>Evaluation</h5>
                    <p>
                        At the end of a semester, students take a generla evaluation
                        test for every subject they're learning.
                    </p>
                </div>
            </div>
        </div>
    </section>
    <section class="text-center">
        <div class="container">
            <img class="ms-image" src="../assets/img/img/Clock-and-Bell.png" alt="">
            <h1>Upcoming Events</h1>
        </div>
    </section>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;
    .ms-img{
        width: 100%;
        img{
            width: 100%;
        }
    }
    section{
        background-color: $brand-primary;
        .ms-image{
            width: 100px;
        }
        .ms-text-bg{
            background-color: #db3838;
            
        }
        h1{
            
            font-weight: bold;
        }
    }
</style>
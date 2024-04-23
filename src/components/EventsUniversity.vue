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
    <section class="text-center pt-5">
        <div class="container">
            <img class="ms-image" src="../assets/img/img/Clock-and-Bell.png" alt="">
            <h1 class="p-4 text-white">Upcoming Events</h1>
            <div class="row gap-5 pt-3 mb-5">
                <div class="col bg-white rounded-4">
                    <div class="p-4 position-relative">
                        <h3>Coaching Sessions</h3>
                        <p class="text-c"><i class="fa-regular fa-calendar-days"></i> 20 May 21.30 PM</p>
                        <p class="text-c">Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
                            Dolor illum adipisci porro beatae consequuntur inventore eligendi, 
                            earum quibusdam cum ipsa fuga aut corporis et! 
                        </p>
                        <div class="position-absolute top-100 start-50 translate-middle">
                            <button class="px-3 py-2 shadow rounded-5 ms-button btn text-white"><i class="fa-solid fa-plus"></i> Find More</button>
                        </div>
                    </div>
                </div>   
                <div class="col bg-white rounded-4">
                    <div class="p-4 position-relative">
                        <h3>Coaching Sessions</h3>
                        <p class="text-c"><i class="fa-regular fa-calendar-days"></i> 24 Mar 18.00 PM</p>
                        <p class="text-c">Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
                            Dolor illum adipisci porro beatae consequuntur inventore eligendi, 
                            earum quibusdam cum ipsa fuga aut corporis et! 
                        </p>
                        <div class="position-absolute top-100 start-50 translate-middle">
                            <button class="px-3 py-2 shadow rounded-5 ms-button btn text-white"><i class="fa-solid fa-plus"></i> Find More</button>
                        </div>
                    </div>
                </div>   
                <div class="col bg-white rounded-4">
                    <div class="p-4 position-relative">
                        <h3>Coaching Sessions</h3>
                        <p class="text-c"><i class="fa-regular fa-calendar-days"></i> 12 Feb 13.30 PM</p>
                        <p class="text-c">Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
                            Dolor illum adipisci porro beatae consequuntur inventore eligendi, 
                            earum quibusdam cum ipsa fuga aut corporis et! 
                        </p>
                        <div class="position-absolute top-100 start-50 translate-middle">
                            <button class="px-3 py-2 shadow rounded-5 ms-button btn text-white"><i class="fa-solid fa-plus"></i> Find More</button>
                        </div>
                    </div>
                </div>   
            </div>
            <div class="p-5">
                <button class="px-5 ms-bg py-4 shadow rounded-5 ms-button btn text-white">View All Events</button>
            </div>
        </div>
    </section>
    <div class="ms-img">
        <img src="../assets/img/svg/svg-1.svg" alt="">
    </div>
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
        .text-c{
            color: grey;
        }
        .ms-button{
            background-color: $brand-primary;
            font-weight: bold;
            font-size: 14px;
        }
        .ms-bg{
            background-color: $brand-secondary;
        }
    }
</style>
<script setup>

</script>

<template>
    <div class="container-fluid mt-5" style="padding-top: 7vw;">
        <div class="row" style="margin: 0.5vw;">
            <div class="col-5" style="border-left: 0.2vw solid white;">
                <div class="d-flex flex-column justify-content-center h-100">
                    <p class="banner-text"><span class="banner-text-first">喵</span>的未來</p>
                    <p class="banner-text" style="margin-left: 4vw;"><span class="banner-text-first">人</span>的希望</p>
                    <div class="w-100 d-flex justify-content-center">
                        <img class="w-50" src="../assets/img/bean-big.svg" alt="bean-big">
                    </div>
                </div>
            </div>
            <div class="col-7">
                <img class="banner-img w-100" src="../assets/img/banner-img.png" alt="banner-img">
            </div>
            
        </div>
        
    </div>
    
</template>

<style scoped>
    .banner-img{
        border-radius: 60px;
        box-shadow: 
            1vw 0.5vw 0 white,
            2vw 1vw 0 white,
            3vw 1.5vw 0 white,
            4vw 2vw 0 white,
            5vw 2.5vw 0 white,
            6vw 3vw 0 white,
            7vw 3.5vw 0 white,
            8vw 4vw 0 white
        ;
    }
    .banner-text{
        font-size: 7.8125vw;
        font-weight: bold;
        color: white;
        line-height: 1em;
    }

    .banner-text-first{
        font-size: 9.375vw;
        color: #FEDB00;
    }
</style>
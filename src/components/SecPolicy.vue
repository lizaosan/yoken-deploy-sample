<script setup>
import { createApp } from 'vue';
import TitleOfSec from './TitleOfSec.vue'


</script>

<template>
    <div class="container-fuild sec-policy mt-2 pt-5">
        <div class="position-absolute">
            <TitleOfSec msg1="政策" msg2="議題"/>
        </div>
        <div class="row my-5">
            <div class="col-12 col-md-4">
                <img class="w-75 ms-5" style="margin-top: 20vw;" src="../assets/img/policy1.png" alt="image">
            </div>
            <div class="col-12 col-md-8 p-3 border-white-left">
                <h3 class="text1">政策1.</h3>
                <h4 class="text2">為毛孩子謀福利！推動寵物醫療保障方案</h4>
                <h5 class="text3">1.設立寵物醫療基金：</h5>
                <p class="text4">每年撥款新台幣 10 億元，專款專用於支援家庭寵物的醫療費用。</p>
                <h5 class="text3">2.提供醫療補助：</h5>
                <p class="text4">每隻寵物每年可獲得高達新台幣 20,000 元的醫療補助，減輕飼主的經濟壓力。</p>
                <h5 class="text3">3.合作動物醫院：</h5>
                <p class="text4">目前已有和超過 200 家動物醫院進行初步的合作討論。</p>
            </div>
        </div>
        <div class="row my-5">
            <div class="col-12 col-md-4">
                <img class="w-75 ms-5" style="margin-top: 10vw;" src="../assets/img/policy2.png" alt="image">
            </div>
            <div class="col-12 col-md-8 p-3 border-white-left">
                <h3 class="text1">政策2.</h3>
                <h4 class="text2">打造休閒天堂！推廣寵物休閒與娛樂場所</h4>
                <h5 class="text3">1.打造休閒天堂！推廣寵物休閒與娛樂場所：</h5>
                <p class="text4">建立寵物公園：每年撥款新台幣 5 億元，用於在各大都市建立專屬的寵物公園。根據初步規劃，預計在第一年內，將在全國範圍內建立至少 10 座寵物公園。</p>
                <h5 class="text3">2.推廣寵物友善商家：</h5>
                <p class="text4">鼓勵商家提供寵物友善的環境，並為參與的商家提供稅收優惠。預計在政策實施後的首年，將有超過 500 家商家加入此計畫。</p>
                <h5 class="text3">3.舉辦寵物活動和工作坊：</h5>
                <p class="text4">與各大寵物社團和組織合作，每年舉辦至少 5 場大型的寵物活動，包括寵物才藝比賽、飼養知識工作坊等。</p>
            </div>
        </div>
        <div class="row my-5">
            <div class="col-12 col-md-4">
                <img class="w-75 ms-5" style="margin-top: 10vw;" src="../assets/img/policy3.png" alt="image">
            </div>
            <div class="col-12 col-md-8 p-3 border-white-left">
                <h3 class="text1">政策3.</h3>
                <h4 class="text2">推廣寵物飼養教育，讓愛更加專業</h4>
                <h5 class="text3">1.設立寵物醫療基金：</h5>
                <p class="text4">每年撥款新台幣 10 億元，專款專用於支援家庭寵物的醫療費用。</p>
                <h5 class="text3">2.提供醫療補助：</h5>
                <p class="text4">每隻寵物每年可獲得高達新台幣 20,000 元的醫療補助，減輕飼主的經濟壓力。</p>
                <h5 class="text3">3.合作動物醫院：</h5>
                <p class="text4">目前已有和超過 200 家動物醫院進行初步的合作討論。</p>
            </div>
        </div>
    </div>
    
</template>

<style scoped>
.sec-policy{
    background-color: #1E42B6;
}
.text1{
    color:#FEDB00;
    font-size: 60px;
    font-weight: bold;
}
.text2{
    color: #FE778B;
    font-size: 55px;
    font-weight: bold;
}
.text3{
    color:#FEDB00;
    font-size: 50px;
    font-weight: bold;
    margin-top: 1.5em;
}
.text4{
    color:white;
    font-size: 35px;
    font-weight: bold;
}
.border-white-left{
    border-left: 5px solid white;
}
</style>
<script setup>
import { createApp } from 'vue';
import TitleOfSec from '../components/TitleOfSec.vue'


</script>

<template>
    <div class="container-fuild sec-notion mt-5 pt-5">
        <div class="row">
            <div class="col-12 col-sm-3">
                <TitleOfSec msg1="候選人" msg2="主張"/>
            </div>
            <div class="col-12 col-sm-9 text">
                <p>　　我堅信，藉由推動更完善的貓咪福利和相關政策，更是間接地投資於台灣的未來。畢竟，民眾的身心健康與工作熱情是推動經濟的核心動力。</p>
                <p>　　透過完善的貓咪福利政策，為台灣的 GDP 經濟帶來巨大效益。因此，我期望能在立法院內推進這些政策，確保每一隻貓咪都能得到他們應有的照顧，同時也為台灣的經濟發展助一臂之力。</p>
            </div>
        </div>
        <div class="row position-relative" style="margin-top: -5vw;">
            <img src="../assets/img/notion-bg.svg" alt="background" style="width:70vw; position: absolute; right: 10vw;">
            <img src="../assets/img/cat1.png" alt="cat" style="width: 20vw; position: absolute; left: 10vw;">
            <p class="text2">讓我們一同護航台灣的幸福經濟，<br/>　　　　　　照顧每一隻貓咪開始。</p>
            
        </div>
    </div>
    
</template>

<style scoped>
    .sec-notion{
        position: relative;
        z-index: 1;
        background-color: #1E42B6;
        min-height: 60vw;
    }
    .text{
        font-size: 2.08vw;
        color:white;
        padding: 7vw;
        padding-top: 4vw;
        font-weight: bold;
    }
    .text2{
        font-size: 3.125vw;
        color:#FEDB00;
        font-weight: bold;
        z-index: 2;
        position: absolute;
        left: 30vw;
        margin-top: 5vw;
    }
</style>
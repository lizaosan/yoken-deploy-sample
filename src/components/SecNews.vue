<script setup>
import { createApp } from 'vue';
import TitleOfSec from './TitleOfSec.vue'


</script>

<template>
    <div class="container-fuild sec-notion mt-2 pt-5">
        <div class="row">
            <div class="col-12 col-sm-3">
                <TitleOfSec msg1="最新" msg2="消息"/>
            </div>
            <div class="col-12 col-sm-9 d-flex flex-column align-items-end">
                <p class="details me-3">更多資訊 <span style="font-size:3.02vw; color:#FEDB00;">▶</span></p>
                <div style="border-bottom: 5px solid white; width: 90%"></div>
            </div>
        </div>
        <div class="row mt-5 p-3">
            <div class="col-12 col-lg-4 news">
                <img src="../assets/img/news1.png" alt="news">
                <h4>參與台北寵物論壇，爭取貓咪友善環境</h4>
                <p>活動一消息內容：炎炎夏日的周六，我走進了台北寵物論壇，帶著一副貓耳髮箍，決定要全力宣傳「貓咪至上」的理念！</p>
            </div>
            <div class="col-12 col-lg-4 news">
                <img src="../assets/img/news2.png" alt="news">
                <h4>帶著你的貓耳，來和我一起走！</h4>
                <p>活動二消息內容：街上氣氛真的很棒，從小孩到大人，甚至有些狗狗朋友都帶著貓耳來找我握手，真的太可愛了！</p>
            </div>
            <div class="col-12 col-lg-4 news">
                <img src="../assets/img/news3.png" alt="news">
                <h4>收容所模特兒大比拼！</h4>
                <p>活動三消息內容：今天的收容所不再是一片寂靜。為了讓更多人認識到這裡的毛孩子，我們舉辦了一場前所未有的「模特兒走秀」！</p>
            </div>
        </div>
    </div>
    
</template>

<style scoped>
.details{
    font-size: 2.83vw;
    color: #000821;
    font-weight: bold;
    background-color: white;
    width:20vw;
    padding:1vw;
    border-radius: 50em;
    line-height: 1em;
    height: 5.4vw;
    display: flex;
    justify-content: center;
    align-items: center;
}
.news img{
    width: 90%;
    border-radius: 20px;
    box-shadow: 
            1.5vw 2vw 0 #000821;
}
.news h4{
    font-weight: bold;
    font-size: 32px;
    margin-top: 3vw;
    color: white;
}
.news p{
    font-weight: bold;
    font-size: 28px;
    color: black;
}
</style>
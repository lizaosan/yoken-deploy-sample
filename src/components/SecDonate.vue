<script setup>
import { createApp } from 'vue';
import TitleOfSec from './TitleOfSec.vue'


</script>

<template>
    <div class="container-fuild sec-donate mt-2 pt-5">
        <TitleOfSec msg1="小額" msg2="捐款"/>
        <img class="donate-bg" src="../assets/img/donate-bg.svg" alt="background">
        <h3>目前小額贊助總金額：<br/>987,655,873</h3>
        <div class="row" style="margin-top: 15vw;">
            <div class="col-12 col-lg-6 d-flex flex-column align-items-center">
                <div class="donate-text">
                    <img src="../assets/img/bean1.svg" alt="icon">
                    <p>捐款新台幣600元</p>
                </div>
                <p class="donate-text2">已有 9957 人贊助</p>
            </div>
            <div class="col-12 col-lg-6 d-flex flex-column align-items-center">
                <div class="donate-text">
                    <img src="../assets/img/bean2.svg" alt="icon">
                    <p>捐款新台幣6000元</p>
                </div>
                <p class="donate-text2">已有 2000 人贊助</p>
            </div>
        </div>
    </div>
    
</template>

<style scoped>
.donate-bg{
    width: 80%;
    margin-left: 10vw;
    margin-top: 6vw;
}
.donate-text{
    display: flex;
    align-items: center;
    justify-content: center;
}
.donate-text img{
    width: 120px;
    z-index: 1;
}
.donate-text p{
    color: #FE778B;
    font-size: 45px;
    font-weight: bold;
    background-color: white;
    padding: 30px;
    border-radius: 50em;
    line-height: 1em;
    margin-left: -20px;
}
.sec-donate h3{
    font-size: 5.7vw;
    line-height: 7.3vw;
    font-weight: bold;
    text-align: center;
    margin-top: -22.5vw;
    
}
.donate-text2{
    color: #000821;
    font-size: 45px;
    font-weight: bold;
}
</style>
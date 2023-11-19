<script setup>
defineProps({
  msg1: {
    type: String,
    required: true,
  },
  msg2: {
    type: String,
    required: true,
  }
})
</script>

<template>
    <h1 class="green"></h1>
    <div class="title">
        <h2>
            <div>{{ msg1 }}</div>
            <div style="margin-left:0.5em;">{{ msg2 }}</div>
        </h2>
    </div>
    
</template>

<style scoped>
    .title{
        width:18.85vw;
        display: flex;
        justify-content: center;
        background-color: white;
        padding-top: 2vw;
        border-radius: 3.125vw;
        box-shadow: 
            1.5vw 2vw 0 #221D3A;
            
        margin-left: 6vw;
    }
    .title h2{
        font-size: 5.2vw;
        font-weight: bold;
        color: #FE778B;
        
    }
</style>
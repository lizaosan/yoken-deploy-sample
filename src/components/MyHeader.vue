<script setup>

</script>

<template>
    <div class="header-parent d-flex flex-column align-items-center w-100">
        <div class="header w-100 d-flex justify-content-between align-items-center text-white">
            <div class="logo d-flex flex-row align-items-center">
                <div class="logo-num">
                    <div>
                        <div class="logo-word">1</div>
                    </div>
                </div>
                <div class="logo-word">喵立翰</div>
            </div>
            <ul class="my-nav d-flex flex-row">
                <li><a href="#SecNotion">候選人主張</a></li>
                <li><a href="#SecNew">最新消息</a></li>
                <li><a href="#SecPolicy">政策議題</a></li>
                <li><a href="#SecDonate">小額捐款</a></li>
                <li><a href="#">聯絡我們</a></li>
            </ul>
        </div>
        <div class="nav-hr"></div>
    </div>
    
</template>

<style scoped>
    .header-parent{
        position: fixed;
        top:0;
        z-index: 10;
    }
    .header{
        height: 7.03vw;
        background: #519BFF;
    }
    .logo{
        margin-left: 2vw;
    }
    .logo-word{
        font-size: 4.42vw;
        font-weight: bold;
        filter: drop-shadow(0.3vw 0.45vw 0px black);
        line-height: 1em;
        margin-right: 0.5vw;
    }
    .logo-num{
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #1A57E3;
        width: 5.2vw;
        height: 5.2vw;
        border-radius: 50em;
        margin-right: 1.5vw;
    }
    .logo-num > div{
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #FE778B;
        width: 4.2vw;
        height: 4.2vw;
        border-radius: 50em;
    }
    .my-nav{
        list-style-type: none;
        font-size: 1.82vw;
        font-weight: bold;
        width: 62.5vw;
        justify-content: space-evenly;
        margin: auto;   

    }
    .my-nav li a{
        padding-top: 0.7vw;
        padding-bottom: 0.3vw;
        padding-right: 1vw;
        padding-left: 1vw;
        color: white;
        text-decoration: none;
    }
    .my-nav li a:hover{
        color: #FE778B;
        background-color: white;
        border-radius: 1vw;
    }

    .nav-hr{
        height: 5px;
        width: 98vw;
        background: white;
    }
</style>
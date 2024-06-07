<template>
    <div class="login_container">
        <img src="../assets/logo.png" class="login_icon"/>
    </div>
</template>

<script></script>

<style lang="less" scoped>
@import '../assets/css/login_global.css';
.login_container
{
    width: 450px;
    height: 300px;
    background-color: #FCFFFC;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    border-radius: 5px;
}
.login_icon
{
    width: 150px;
    height: 150px;
    border: 10px solid white;
    border-radius: 150px;
    overflow: hidden;
    position: relative;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: aliceblue;
}
</style>

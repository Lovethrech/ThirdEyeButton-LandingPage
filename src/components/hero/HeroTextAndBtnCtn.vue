<script setup>
import HeroTextCtn from "./HeroTextCtn.vue";
</script>

<template>
    <div id="hero-text-and-btn-ctn">
        <div id="hero-text-and-btn-ctn-mini-ctn">
            <HeroTextCtn></HeroTextCtn>
        </div>
    </div>
</template>

<style scoped>
#hero-text-and-btn-ctn{
    background: url("/public/hero-top-left.png") top left/auto 16vh no-repeat,
    url("/public/hero-top-right.png") top right/30vh no-repeat,
    url("/public/hero-bottom-right.png") bottom right 24vh/24vh no-repeat;
    height: 70vh;
    display: flex;
    justify-content: center;
}
#hero-text-and-btn-ctn-mini-ctn{
    width: 50%;
    height:40vh;
    background-color: orange;
}
</style>
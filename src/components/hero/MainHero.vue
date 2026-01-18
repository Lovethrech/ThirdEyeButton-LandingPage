<script setup>
import HeroTextAndBtnCtn from './HeroTextAndBtnCtn.vue';
</script>

<template>
    <section 
        class="main-hero">
    
        <HeroTextAndBtnCtn></HeroTextAndBtnCtn>
    </section>
</template>

<style scoped>
.main-hero{
    min-height: 90vh;
    background: linear-gradient(to bottom, #cae0ff, #ffffff);
    padding: 1vh 4vw;
}
</style>
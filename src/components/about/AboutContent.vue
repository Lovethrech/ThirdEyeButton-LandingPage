<script setup>
import AboutTitle from './AboutTitle.vue';
import AboutDesc from './AboutDesc.vue';
</script>

<template>
    <section class="about-content">
        <AboutTitle></AboutTitle>
        <AboutDesc></AboutDesc>
    </section>
</template>

<style scoped>
.about-content{
    width: 100%;
    min-height: 100vh;
    padding: 2vh 4vw;
}
</style>
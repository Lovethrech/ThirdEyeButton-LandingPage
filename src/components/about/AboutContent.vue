<script setup>
import AboutTitle from './AboutTitle.vue';
import AboutDesc from './AboutDesc.vue';
</script>

<template>
    <section class="about-content">
        <div id="about-content-mini-ctn">
            <AboutTitle></AboutTitle>
            <AboutDesc></AboutDesc>
        </div>
    </section>
</template>

<style scoped>
.about-content{    
    width: 100%;
    min-height: 100vh;
    padding: 6vh 4vw;
}
#about-content-mini-ctn{
    background-color: orange;
    height: 70%;
}
</style>
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
    min-height: 70vh;
    padding: 1vh 0 3vh;
    display: flex;
    flex-direction: column;
    gap:6vh;
}
@media screen and (max-width:990px) and (min-width:346px){
    .about-content{
        display: flex;
        justify-content: center;
        align-items: center;
    }
    #about-content-mini-ctn{
        gap:0;
        padding:0;
    }
}
</style>
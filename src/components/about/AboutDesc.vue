<script setup>
import AboutExploreBtn from './AboutExploreBtn.vue';
</script>

<template>
    <div id="about-desc-ctn">
        <div id="about-desc-ctn-mini-ctn">
            <h4 id="about-desc-name-title">
                Our Mission
            </h4>
            <br/>
            <p id="about-desc">
                ThirdEyeButton is an IT solution company that provides a
                default website interface for registered university clients.
                Our system offers sophisticated exam scheduling and
                management tools, ensuring a seamless and efficient
                process for both administrators and students. With a focus
                on innovation and user-centric design, we aim to
                streamline the exam scheduling experience for
                educational institutions
            </p>
            <br/>
            <AboutExploreBtn></AboutExploreBtn>
        </div>
    </div>
</template>

<style scoped>
#about-desc-ctn{
    min-height: 50vh;
    background: url("/public/about-top-left.png") top left/26vh  no-repeat,
    url("/public/about-bottom-right.png") bottom right/ 34vh no-repeat;
    display: flex;
    justify-content: right;
}
#about-desc-ctn-mini-ctn{
    width:40%;
}
#about-desc-name-title{
    font-size: 1.6vh;
    font-family: "Cormorant Unicase", serif;
}
#about-desc{
    line-height: 4vh;
    font-size:2vh;
    font-family: "Roboto Condensed", sans-serif;
}

@media screen and (max-width:990px) and (min-width:346px){
    #about-desc-ctn{
        background: url("/public/about-top-left.png") top right/26vh no-repeat;
        padding-top:20vh;
    }
    #about-desc-ctn-mini-ctn{
        width: 100%;
    }
    #about-desc{
        text-align:justify;
    }
}
</style>
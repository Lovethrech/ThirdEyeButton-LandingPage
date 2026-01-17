<script setup>
import HeroTextCtn from "./HeroTextCtn.vue";
import HeroSignUpBtn from "./HeroSignUpBtn.vue";
</script>

<template>
    <div 
        id="hero-text-and-btn-ctn"
    >
        <div 
            id="hero-text-and-btn-ctn-mini-ctn"
        >
            <HeroTextCtn></HeroTextCtn>
            <br/>
            <HeroSignUpBtn></HeroSignUpBtn>
        </div>
    </div>
</template>

<style scoped>
#hero-text-and-btn-ctn{
background: url("/public/hero-top-left.png") top left/auto 16vh no-repeat,
    url("/public/hero-top-right.png") top right/30vh no-repeat,
    url("/public/hero-bottom-right.png") bottom right 34vh/24vh no-repeat
;
margin-top:4vh;
height: 60vh;
display: flex;
justify-content: center;
}
#hero-text-and-btn-ctn-mini-ctn{
    background-color: transparent;
    width: 50%;
}

@media screen and (max-width:320px) {
    #hero-text-and-btn-ctn{
        background: url("/public/hero-bottom-right.png") bottom 20vw center/70vw no-repeat;
        margin-top:16vw;
    }
    #hero-text-and-btn-ctn-mini-ctn{
        width: 100%;
    }
}

@media screen and (max-width:990px)  and (min-width:321px){
    #hero-text-and-btn-ctn{
        background: url("/public/hero-bottom-right.png") bottom center/34vh no-repeat;
        margin-top:6vh;
    }
    #hero-text-and-btn-ctn-mini-ctn{
        width: 100%;
    }
}

@media screen and (min-height:1360px) {
    #hero-text-and-btn-ctn{
        background: url("/public/hero-bottom-right.png") bottom center/34vh no-repeat;
        margin-top:6vh;
    }
    #hero-text-and-btn-ctn-mini-ctn{
        width: 100%;
    }
}
</style>
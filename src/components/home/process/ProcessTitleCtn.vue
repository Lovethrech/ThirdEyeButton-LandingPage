<script setup>
import { defineProps } from 'vue';

const {title, tag, desc}=defineProps(['title', 'tag', 'desc']);
</script>

<template>
    <div 
        class="process-title-ctn"
    >
        <div 
            class="process-title-ctn-mini-ctn"
        >
            <h3 
                class="process-title-name"
            >
                {{ title }}
            </h3>
            <p 
                class="process-title-tag"
            >   {{ tag }}
                
            </p>
            <div class="process-title-desc-ctn" v-html="desc"></div>
        </div>
    </div>
</template>

<style scoped>
.process-title-ctn{
    width: 100%;
    border-bottom: 0.1vh solid #000000;
}
.process-title-name{
    font-size: 6vh;
    font-family: "Old Standard TT", serif;
    font-optical-sizing: auto;
    font-weight: 500;
}
.process-title-tag{
    margin: 6vh 0 2vh;
    font-family: "Cormorant Unicase", serif;
    font-size: 1.6vh;
    letter-spacing: 0.3vh;
}
.process-title-desc-ctn{
    font-size: 2vh;
    font-family: "Roboto Condensed", sans-serif;
    line-height: 4vh;
    margin-bottom: 3vh;
}

@media screen and (max-width:345px) {
    .process-title-name, .process-title-tag{
        text-align: center;
    }
    .process-title-tag{
        margin:0;
    }
}
@media screen and (max-width:990px) and (min-width:346px){
    .process-title-name, .process-title-tag, .process-title-desc-ctn{
        text-align: center;
    }
    .process-title-tag{
        margin:0;
    }

}
</style>
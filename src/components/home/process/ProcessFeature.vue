<script setup>
import { defineProps } from 'vue';

const {subTitle, title, desc}=defineProps(['subTitle', "title", "desc"]);
</script>

<template>
    <div class="process-feature">
        <p class="process-feature-sub-title">
            {{subTitle}}
        </p>
        <p class="process-feature-title">
            {{title}}
        </p>
        <p class="process-feature-desc">
            {{ desc }}
        </p>
    </div>
</template>

<style scoped>
.process-feature-sub-title{
    font-family: "Cormorant Unicase", serif;
}
.process-feature-title{
    font-size: 2.6vh;
    font-family: "Old Standard TT", serif;
    margin: 2vh 0;
}
.process-feature-desc{
    font-size:2vh;
    font-family: "Roboto Condensed", sans-serif;
    font-weight: 300;
    line-height: 4vh;
}
</style>
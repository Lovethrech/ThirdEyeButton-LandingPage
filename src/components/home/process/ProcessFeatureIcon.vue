<script setup>
import { defineProps } from 'vue';

const {imgSrc, imgAlt}=defineProps(['imgSrc', 'imgAlt']);
</script>

<template>
    <div class="process-feature-icon-ctn">
        <img :src="imgSrc" :alt="imgAlt">
    </div>
</template>

<style scoped>
.process-feature-icon-ctn{
    margin: auto 0;
    width:20vh;
}
.process-feature-icon-ctn img{
    width: 100%;
}
</style>
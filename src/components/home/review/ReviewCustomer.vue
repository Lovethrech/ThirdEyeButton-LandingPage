<script setup>
import { defineProps } from 'vue';

const {name, desc}=defineProps(['name', 'desc']);
</script>

<template>
    <div class="review-customer">
        <p class="review-customer-name">
            {{ name }}
        </p>
        <div class="review-customer-comment-ctn" v-html="desc"></div>
    </div>
</template>

<style scoped>
.review-customer{
    display:flex;
    flex-direction: row;
    gap:3vw;
}
.review-customer-name{
    width: 46%;
    font-size: 2vh;
    font-family: "Old Standard TT", serif;
}
.review-customer-comment-ctn{
    font-size:1.6vh;
    font-family: "Roboto Condensed", sans-serif;
    font-weight: 300;
    line-height: 4vh;
}
</style>
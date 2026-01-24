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
<script setup>
import { defineProps } from 'vue';

const [name, link]=defineProps({"name", "link"});
</script>

<template>
    <div class="header-menu-ctn">
        <RouterLink :to="{link}">
            <p class="header-menu-name">
                {{ name }}
            </p>
        </RouterLink>
    </div>
</template>
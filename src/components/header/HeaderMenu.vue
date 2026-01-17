<script setup>
import { defineProps } from 'vue';

const {name, link}=defineProps(["name", "link"]);
</script>

<template>
    <div 
        class="header-menu-ctn"
    >
        <RouterLink 
            :to="{link}"
        >
            <p 
                class="header-menu-name"
            >
                {{ name }}
            </p>
        </RouterLink>
    </div>
</template>

<style scoped>
.header-menu-name{
    text-transform: capitalize;
    font-size: 1.6vh;
}
.header-menu-name:hover{
    cursor: pointer;
    transform: scale(1.1);
    transition: all .2s;
}

@media screen and (max-width:990px) {
    .header-menu-ctn{
        margin: 3vh;
    }
    .header-menu-name{
        font-size: 4vh;
    }
}
</style>
<script setup>
import HeaderMenuDetails from "@/data/header-menu-details.json";
import HeaderMenu from './HeaderMenu.vue';

console.log(HeaderMenuDetails.name)
</script>

<template>
    <div class="header-menu-ctn-main-ctn">
        <div v-for="HeaderMenuDetail in HeaderMenuDetails" :key="HeaderMenuDetail.id" class="header-menu-ctn-mini-ctn">
            <HeaderMenu 
                :name="HeaderMenuDetail.name" 
                :link="HeaderMenuDetail.link"
            >
            </HeaderMenu>
        </div>
    </div>
</template>
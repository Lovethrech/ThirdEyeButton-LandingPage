<script setup>
import HeaderMenuDetails from "../data/header-menu-details.json";
import HeaderMenu from './HeaderMenu.vue';
</script>

<template>
    <div class="header-menu-ctn-main-ctn">
        <div v-for="HeaderMenuDetail in HeaderMenuDetails" :key="HeaderMenuDetail.id" class="header-menu-ctn-mini-ctn">
            <HeaderMenu 
                :name="name" 
                :link="link"
            >
            </HeaderMenu>
        </div>
    </div>
</template>
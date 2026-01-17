<script setup>
import HeaderMenuDetails from "@/data/header-menu-details.json";
import HeaderMenu from './HeaderMenu.vue';

console.log(HeaderMenuDetails.name)
</script>

<template>
    <div 
        class="header-menu-ctn-main-ctn">
        <div 
            v-for="HeaderMenuDetail in HeaderMenuDetails"  
            class="header-menu-ctn-mini-ctn" 
            :key="HeaderMenuDetail.id"
        >
            <HeaderMenu 
                :name="HeaderMenuDetail.name" 
                :link="HeaderMenuDetail.link"
            >
            </HeaderMenu>
        </div>
    </div>
</template>

<style scoped>
.header-menu-ctn-main-ctn{
    display:flex;
    flex-direction: row;
    gap: 1.4vw;
    margin: auto 0;
}
</style>
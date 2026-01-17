<script setup>
import HeaderLogo from './header/HeaderLogo.vue';
import HeaderMenuCtn from './header/HeaderMenuCtn.vue';
</script>

<template>
    <header>
        <HeaderLogo></HeaderLogo>
        <HeaderMenuCtn></HeaderMenuCtn>
    </header>
</template>

<style scoped>
header{
    background-color: #cae0ff;
    padding: 1vh 4vw;
    display:flex;
    flex-direction: row;
    justify-content: space-between;
}
</style>
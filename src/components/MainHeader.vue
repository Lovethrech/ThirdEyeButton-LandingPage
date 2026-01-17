<script setup>
import HeaderLogo from './header/HeaderLogo.vue';
import HeaderNavCtn from './header/HeaderNavCtn.vue';
</script>

<template>
    <header>
        <HeaderLogo></HeaderLogo>
        <HeaderNavCtn></HeaderNavCtn>
    </header>
</template>

<style scoped>
header{
    background-color: #cae0ff;
    padding: 1vh 4vw;
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    border: 0;
}
</style>
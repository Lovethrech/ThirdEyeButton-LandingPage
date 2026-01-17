<script setup>
import HeaderMenuCtn from './HeaderMenuCtn.vue';
import HeaderClientBtn from './HeaderClientBtn.vue';
</script>

<template>
    <div class="header-nav-ctn">
        <HeaderMenuCtn></HeaderMenuCtn>
        <HeaderClientBtn></HeaderClientBtn>
    </div>
</template>

<style scoped>
.header-nav-ctn{
    margin: auto 0;
    display: flex;
    flex-direction: row;
    gap:2vw;
}
</style>
<script setup>
import {ref, onMounted, computed} from 'vue';
import HeaderLogo from './header/HeaderLogo.vue';
import HeaderNavCtn from './header/HeaderNavCtn.vue';
import HeaderMenuIcon from './header/HeaderMenuIcon.vue';

const screenWidth=ref(window.innerWidth);

onMounted(()=>{
    const screenView= computed(()=>screenWidth);
    console.log(screenView.value._value);
});



</script>

<template>
    <header>
        <HeaderLogo></HeaderLogo>
        <HeaderNavCtn></HeaderNavCtn>
        <HeaderMenuIcon></HeaderMenuIcon>
    </header>
</template>

<style scoped>
header{
    position:sticky;
    background-color: #cae0ff;
    padding: 0.4vh 4vw;
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    border: 0.02vh solid #000000;
}
</style>
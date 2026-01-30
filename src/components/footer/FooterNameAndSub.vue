<script setup>
import FooterName from './FooterName.vue';
import FooterSubContent from './FooterSubContent.vue';
</script>

<template>
    <div class="footer-name-and-sub">
        <FooterName></FooterName>
        <FooterSubContent></FooterSubContent>
    </div>
</template>

<style scoped>
.footer-name-and-sub{
    width: 50%;
    min-height: 40vh;
    background: linear-gradient(to right, #ffffff, #cae0ff);
    padding: 3vh 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
</style>
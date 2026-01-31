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
    min-height: 50vh;
    background: linear-gradient(to right, #ffffff, #cae0ff);
    padding: 3vh 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

@media screen and (max-width:990px) {
    .footer-name-and-sub{
        width: 100%;
        background: linear-gradient(to bottom, #ffffff, #cae0ff);
        
    }
}
</style>
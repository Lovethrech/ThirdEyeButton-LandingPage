<script setup>
import FooterTelAddrIcon from './FooterTelAddrIcon.vue';
</script>

<template>
    <div class="footer-link-and-policy">
        <div class="footer-link-and-policy-mini-ctn">
            <FooterTelAddrIcon></FooterTelAddrIcon>
        </div>
    </div>
</template>

<style scoped>
.footer-link-and-policy{
    width: 50%;
    min-height: 50vh;
    background: linear-gradient(to left, #ffffff, #cae0ff);
    padding: 3vh 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
</style>
<script setup>
import FooterTelAddrIcon from './FooterTelAddrIcon.vue';
import FooterPolicyCtn from './FooterPolicyCtn.vue';
</script>

<template>
    <div class="footer-link-and-policy">
        <div class="footer-link-and-policy-mini-ctn">
            <FooterTelAddrIcon></FooterTelAddrIcon>
            <FooterPolicyCtn></FooterPolicyCtn>
        </div>
    </div>
</template>

<style scoped>
.footer-link-and-policy, .footer-link-and-policy-mini-ctn{
    width: 50%;
    display: flex;
}
.footer-link-and-policy{
    min-height: 50vh;
    background: linear-gradient(to left, #ffffff, #cae0ff);
    padding: 3vh 0;
    justify-content: right;
    align-items:end;
}
.footer-link-and-policy-mini-ctn{
    height: 50%;
    flex-direction: row;
    justify-content: space-between;
}

@media screen and (max-width:990px) {
    .footer-link-and-policy, .footer-link-and-policy-mini-ctn{
        width: 100%;
        height: 100%;
    }
    .footer-link-and-policy{
        background: transparent;
        align-items: flex-start;
        padding: 0;
    }
}
</style>
<script setup>
import FooterNameAndSub from './footer/FooterNameAndSub.vue';
import FooterLinkAndPolicy from './footer/FooterLinkAndPolicy.vue';
</script>

<template>
    <footer>
        <div class="footer-main-ctn">
            <FooterNameAndSub></FooterNameAndSub>
            <FooterLinkAndPolicy></FooterLinkAndPolicy>
        </div>
    </footer>
</template>

<style scoped>
footer{
    padding: 0 4vw;
}
.footer-main-ctn{
    display: flex;
    flex-direction: row;
}

@media screen and (max-width:990px) {
    footer{
        border-top: 0.5vh double #000000;
        background: linear-gradient(to bottom, #ffffff, #cae0ff);
    }
    .footer-main-ctn{
        flex-direction: column;
    }
}
</style>
<script setup>
import ContactHeaderCtn from './ContactHeaderCtn.vue';
</script>

<template>
    <section class="contact-content">
        <div class="contact-content-mini-ctn">
            <ContactHeaderCtn></ContactHeaderCtn>
        </div>
    </section>
</template>

<style scoped>
.contact-content{
    width: 100%;
    min-height: 100vh;
    background-color: #ffffff;
    padding: 4vh 4vw;
    display: flex;
    justify-content: center;
    align-items: center;
}
.contact-content-mini-ctn{
    width:50%;
    background-color: orange;
    padding:2vh 3vw;
}
</style>
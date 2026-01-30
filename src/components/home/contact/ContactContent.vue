<script setup>
import ContactHeaderCtn from './ContactHeaderCtn.vue';
import ContactFormCtn from './ContactFormCtn.vue';
</script>

<template>
    <section 
        class="contact-content"
    >
        <div 
            class="contact-content-mini-ctn"
        >
            <ContactHeaderCtn></ContactHeaderCtn>
            <ContactFormCtn></ContactFormCtn>
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
    padding:2vh 3vw;
}
</style>
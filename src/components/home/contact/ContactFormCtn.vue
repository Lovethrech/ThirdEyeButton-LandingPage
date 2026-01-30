<script setup>
import contactLabelAndInputFormats from "@/data/contact-label-and-input-formats.json";
import ContactFormLabelAndInput from './ContactFormLabelAndInput.vue';
</script>

<template>
    <div class="contact-form-ctn">
        <div class="contact-form-mini-ctn" v-for="contactLabelAndInputFormat in contactLabelAndInputFormats" :key="contactLabelAndInputFormat.id">
            <ContactFormLabelAndInput></ContactFormLabelAndInput>
        </div>
    </div>
</template>

<style scoped>
.contact-form-ctn{
    margin: 4vh 0;
}
</style>
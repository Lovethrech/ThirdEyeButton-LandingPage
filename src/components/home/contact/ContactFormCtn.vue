<script setup>
import contactLabelAndInputFormats from "@/data/contact-label-and-input-formats.json";
import ContactFormLabelAndInput from './ContactFormLabelAndInput.vue';
import ContactFormBtn from "./ContactFormBtn.vue";
</script>

<template>
    <div 
        class="contact-form-ctn"
    >
        <div 
            class="contact-form-mini-ctn" 
            v-for="contactLabelAndInputFormat in contactLabelAndInputFormats" 
            :key="contactLabelAndInputFormat.id"
        >
            <ContactFormLabelAndInput
                :labelName="contactLabelAndInputFormat.labelName"
                :labelFor="contactLabelAndInputFormat.labelFor"
                :inputType="contactLabelAndInputFormat.inputType"
            >
            </ContactFormLabelAndInput>
        </div>
        <ContactFormBtn></ContactFormBtn>
    </div>
</template>

<style scoped>
.contact-form-ctn{
    margin: 4vh 0;
}
.contact-form-mini-ctn{
    margin: 2vh 0;
}
</style>
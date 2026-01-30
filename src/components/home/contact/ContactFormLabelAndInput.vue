<script setup>
import { defineProps } from 'vue';

const {labelName, labelFor, inputType}=defineProps(["labelName", "labelFor", "inputType"]);
</script>

<template>
    <div 
        class="contact-form-label-and-input-ctn"
    >
        <label 
            :for="labelFor" 
            class="contact-form-label-and-input-ctn-label"
        >
            {{labelName}}
        </label>
        <input 
            :type="inputType" 
            class="contact-form-label-and-input-ctn-input"
            required
        >
    </div>
</template>

<style scoped>
.contact-form-label-and-input-ctn{
    display: flex;
    flex-direction: column;
}
.contact-form-label-and-input-ctn-label{
    font-size: 1.8vh;
}
.contact-form-label-and-input-ctn-input{
    margin: 1vh 0;
    border: 0;
    border-bottom: 0.2vh solid #000000;
    padding: 1vh 1vw;
    font-size: 1.8vh;
}
</style>
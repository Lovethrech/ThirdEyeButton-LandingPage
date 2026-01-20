<script setup>
import ProcessTitleCtn from '@/components/home/process/ProcessTitleCtn.vue';
import ProcessFeatureCtn from './ProcessFeatureCtn.vue';
</script>

<template>
    <div 
        class="process-content"
    >
        <div 
            class="process-content-mini-ctn"
        >
            <ProcessTitleCtn></ProcessTitleCtn>
            <ProcessFeatureCtn></ProcessFeatureCtn>
        </div>
    </div>
</template>

<style scoped>
.process-content{
    background: linear-gradient(to bottom, #ffffff, #cae0ff);
    width: 100%;
    min-height: 100vh;
    padding: 5vh 4vw;
}

@media screen and (max-width:990px) {
    .process-content{
        padding:8vh 4vw;
    }
}
</style>
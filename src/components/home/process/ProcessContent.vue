<script setup>
import processAndReviewDetails from "@/data/process-and-review-details.json";
import ProcessTitleCtn from '@/components/home/process/ProcessTitleCtn.vue';
import ProcessFeatureCtn from './ProcessFeatureCtn.vue';
</script>

<template>
    <section 
        class="process-content"
    >
        <div 
            class="process-content-mini-ctn"
        >
            <ProcessTitleCtn
                :title="processAndReviewDetails[0].title"
            >
            </ProcessTitleCtn>
            <ProcessFeatureCtn></ProcessFeatureCtn>
        </div>
    </section>
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
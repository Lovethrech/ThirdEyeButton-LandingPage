<script setup>
import processAndReviewDetails from "@/data/process-and-review-details.json";
import ProcessTitleCtn from '../process/ProcessTitleCtn.vue';
</script>

<template>
    <section class="review-content">
        <div id="review-content-mini-ctn">
            <ProcessTitleCtn
                :title="processAndReviewDetails[0].title"
                :tag="processAndReviewDetails[0].tag"
                :desc="processAndReviewDetails[0].desc"
            >
            </ProcessTitleCtn>
        </div>
    </section>
</template>

<style scoped>
.review-content{
    background: linear-gradient(to bottom, #cae0ff, #ffffff);
    height: 100%;
}
</style>
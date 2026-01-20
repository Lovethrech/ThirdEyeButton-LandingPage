<script setup>
import ProcessFeature from './ProcessFeature.vue';
</script>

<template>
    <div class="process-feature-ctn">
        <div id="process-feature-main-ctn">
            <div id="process-feature-mini-ctn">
                <ProcessFeature></ProcessFeature>
            </div>
        </div>
    </div>
</template>

<style scoped>
.process-feature-ctn{
    display:flex;

}
#process-feature-main-ctn{
    width:40%;
    background-color: red;
    padding: 4vh 0;
    border-bottom: 0.1vh solid #000000;
}
</style>
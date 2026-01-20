<script setup>
import ProcessFeature from './ProcessFeature.vue';
import ProcessFeatureIcon from './ProcessFeatureIcon.vue';
</script>

<template>
    <div class="process-feature-ctn">
        <div id="process-feature-main-ctn">
            <div id="process-feature-mini-ctn">
                <ProcessFeature></ProcessFeature>
                <ProcessFeatureIcon></ProcessFeatureIcon>
            </div>
        </div>
    </div>
</template>

<style scoped>
.process-feature-ctn{
    display:flex;
    justify-content: right;
}
#process-feature-main-ctn{
    width:40%;    
    display: flex;
    flex-direction: column;
    gap:3vh;    
}
#process-feature-mini-ctn{
    padding: 4vh 0;    
}
#process-feature-mini-ctn:nth-child(2){
    border-top: 0.1vh solid #000000;
    border-bottom: 0.1vh solid #000000;
}
</style>
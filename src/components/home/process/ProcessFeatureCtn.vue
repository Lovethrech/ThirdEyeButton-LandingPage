<script setup>
import processFeatureDetails from "@/data/process-feature-details.json";
import ProcessFeature from './ProcessFeature.vue';
import ProcessFeatureIcon from './ProcessFeatureIcon.vue';

console.log(processFeatureDetails(0));
</script>

<template>
    <div class="process-feature-ctn">
        <div id="process-feature-main-ctn">
            <div id="process-feature-mini-ctn" v-for="processFeatureDetail in processFeatureDetails" :key="processFeatureDetail.id">
                <ProcessFeature
                    :subTitle="processFeatureDetail.subTitle"
                    :title="processFeatureDetail.title"
                    :desc="processFeatureDetail.desc"
                >
                </ProcessFeature>
                <ProcessFeatureIcon
                    :imgSrc="processFeatureDetail.imgSrc"
                    :imgAlt="processFeatureDetail.imgAlt"
                >
                </ProcessFeatureIcon>
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
    width:44%;    
    display: flex;
    flex-direction: column;
    gap:3vh;    
}
#process-feature-mini-ctn{
    padding: 4vh 0;  
    display: flex;  
    flex-direction: row;
    justify-content: space-between;
}
#process-feature-mini-ctn:nth-child(2){
    border-top: 0.1vh solid #000000;
    border-bottom: 0.1vh solid #000000;
}
</style>
<script setup>
import MainHero from '@/components/home/hero/MainHero.vue';
import AboutContent from '@/components/home/about/AboutContent.vue';
import ProcessContent from '@/components/home/process/ProcessContent.vue';
import ReviewContent from '@/components/home/review/ReviewContent.vue';
</script>

<template>
  <main>
    <MainHero></MainHero>
    <AboutContent></AboutContent>
    <ProcessContent></ProcessContent>
    <ReviewContent></ReviewContent>
  </main>
</template>

<style scoped>
main{
  min-height:100%;
}
</style>

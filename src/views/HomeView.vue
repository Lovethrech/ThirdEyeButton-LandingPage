<script setup>
import MainHero from '@/components/home/hero/MainHero.vue';
import AboutContent from '@/components/home/about/AboutContent.vue';
import ProcessContent from '@/components/home/process/ProcessContent.vue';
import ReviewContent from '@/components/home/review/ReviewContent.vue';
import ContactContent from "@/components/home/contact/ContactContent.vue";
</script>

<template>
  <main>
    <MainHero></MainHero>
    <AboutContent></AboutContent>
    <ProcessContent></ProcessContent>
    <ReviewContent></ReviewContent>
    <ContactContent></ContactContent>
  </main>
</template>

<style scoped>
main{
  min-height:100%;
}
</style>

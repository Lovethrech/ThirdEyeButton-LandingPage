<script setup>
import MainHeader from "@/components/MainHeader.vue";
import MainHero from '@/components/home/hero/MainHero.vue';
import AboutContent from '@/components/home/about/AboutContent.vue';
import ProcessContent from '@/components/home/process/ProcessContent.vue';
import ReviewContent from '@/components/home/review/ReviewContent.vue';
import ContactContent from "@/components/home/contact/ContactContent.vue";
import MainFooter from '@/components/MainFooter.vue';
</script>

<template>
  <main>
    <MainHeader></MainHeader>
    <MainHero></MainHero>
    <AboutContent></AboutContent>
    <ProcessContent></ProcessContent>
    <ReviewContent></ReviewContent>
    <ContactContent></ContactContent>
    <MainFooter></MainFooter>
  </main>
</template>

<style scoped>
main{
  min-height:100vh;
}
</style>

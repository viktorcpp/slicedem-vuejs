
<script setup>

import Header from "@/components/header/Header.vue";
import Footer from "@/components/footer/Footer.vue";
import MainTitle from "@/components/main_title/MainTitle.vue";
import AboutUs from "@/components/aboutus/AboutUs.vue";
import WGallery from "@/components/wgallery/WGallery.vue";
import Study from "@/components/study/Study.vue";
import StudyOn from "@/components/studyon/StudyOn.vue";
import Creat from "@/components/creat/Creat.vue";

</script>

<template>
  <Header />
  <main>
    <MainTitle />
    <AboutUs />
    <WGallery />
    <Study />
    <StudyOn />
    <Creat />
  </main>
  <Footer />
</template>

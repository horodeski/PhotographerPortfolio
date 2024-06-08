<script setup>
import AboutMe from '@/components/AboutMe.vue'
import NavBar from '@/components/NavBar.vue'
import FooterSection from '@/components/FooterSection.vue'
import ContactSection from '@/components/ContactSection.vue'
import HeroSection from '@/components/HeroSection.vue'
import MyProjects from '@/components/ProjectsSection.vue'
</script>

<template>
  <NavBar />
  <main>
    <HeroSection />
    <AboutMe />
    <MyProjects />
    <ContactSection />
  </main>
  <FooterSection />
</template>

<script setup>
import NavigationDesktop from './components/NavigationDesktop.vue';
import SkillsOverview from './components/SkillsOverview.vue';
import CarreerOverview from './components/CarreerOverview.vue';
import CertificateOverview from './components/CertificateOverview.vue';
</script>

<template>
  <header id="header">
    <a href="https://little-pumpkin-design.com/"><img src="@/assets/images/own_logo/Logo_Schrift_colored.png" width="300px" alt="Logo"></a>
    <NavigationDesktop />
  </header>
  <main>
    <h1>Skill</h1>
    <SkillsOverview />
    <h1>Lebenslauf</h1>
    <CarreerOverview />
    <h1>Zertifikate</h1>
    <CertificateOverview />
  </main>
</template>
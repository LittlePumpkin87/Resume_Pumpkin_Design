<script setup>
import NavigationDesktop from './components/NavigationDesktop.vue';
import SkillsOverview from './components/SkillsOverview.vue';
import CarreerOverview from './CarreerOverview.vue';
</script>

<template>
  <header id="header">
    <a href="index.html"><img src="@/assets/images/own_logo/Logo_Schrift_colored.png" width="300px" alt="Logo"></a>
    <NavigationDesktop  />
  </header>
  <main>
<SkillsOverview />
<CarreerOverview />
  </main>
</template>
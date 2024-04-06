<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})

import CarreerPath2024 from './components/CarreerPath2024.vue';
import CarreerPath2023 from './components/CarreerPath2023.vue';
import CarreerPath2022 from './components/CarreerPath2022.vue';
import CarreerPath2021 from './components/CarreerPath2021.vue';
import CarreerPath2017 from './components/CarreerPath2017.vue';
import CarreerPath2015 from './components/CarreerPath2015.vue';
import CarreerPath2013 from './components/CarreerPath2013.vue';
import CarreerPath2012 from './components/CarreerPath2012.vue';
import CarreerPath2011 from './components/CarreerPath2011.vue';
import CarreerPath2010 from './components/CarreerPath2010.vue';
import CarreerPath2005 from './components/CarreerPath2005.vue';

</script>

<template>

  <div class="timeline">
    <CarreerPath2024 />
    <CarreerPath2023 />
    <CarreerPath2022 />
    <CarreerPath2021 />
    <CarreerPath2017 />
    <CarreerPath2015 />
    <CarreerPath2013 />
    <CarreerPath2012 />
    <CarreerPath2011 />
    <CarreerPath2010 />
    <CarreerPath2005 />
  </div>

</template>
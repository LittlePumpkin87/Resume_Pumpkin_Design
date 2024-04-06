<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})

import CarreerPath2024 from './CarreerComponents/CarreerPath2024.vue';
import CarreerPath2023 from './CarreerComponents/CarreerPath2023.vue';
import CarreerPath2022 from './CarreerComponents/CarreerPath2022.vue';
import CarreerPath2021 from './CarreerComponents/CarreerPath2021.vue';
import CarreerPath2017 from './CarreerComponents/CarreerPath2017.vue';
import CarreerPath2015 from './CarreerComponents/CarreerPath2015.vue';
import CarreerPath2013 from './CarreerComponents/CarreerPath2013.vue';
import CarreerPath2012 from './CarreerComponents/CarreerPath2012.vue';
import CarreerPath2011 from './CarreerComponents/CarreerPath2011.vue';
import CarreerPath2010 from './CarreerComponents/CarreerPath2010.vue';
import CarreerPath2005 from './CarreerComponents/CarreerPath2005.vue';

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
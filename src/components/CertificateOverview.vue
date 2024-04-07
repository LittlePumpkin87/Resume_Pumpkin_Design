<template>
  <div class="CertGrid">

    <div class="Cert">
      <div class="Pumpkin Small"></div>
      <h3 class="CertName">geprüfte Webentwicklerin ILS</h3>
    </div>

    <div class="Cert">
      <div class="Pumpkin Small"></div>
      <h3 class="CertName">staatlich anerkannte Grafikdesignerin ILS</h3>
    </div>

    <div class="Cert">
      <div class="Pumpkin Small"></div>
      <h3 class="CertName">Ausbildereignungsprüfung AEVO</h3>
    </div>

    <div class="Cert">
      <div class="Pumpkin Small"></div>
      <h3 class="CertName">Ersthelfer</h3>
    </div>

    <div class="Cert">
      <div class="Pumpkin Small"></div>
      <h3 class="CertName">Kauffrau im Einzelhandel</h3>
    </div>
  </div>
</template>

<style scoped>
.CertGrid {
  display: grid;
  grid-template-columns: 1fr;
  border-radius: 2rem 0rem 2rem 0.5rem;
  border-bottom: solid 0.4rem var(--accentOrange);
  border-left: solid 0.4rem var(--accentOrange);
}

.Cert {
  display: flex;
  align-items: center;
}

.Small {
  min-width: 2rem;
  min-height: 2rem;
  max-width: 2rem;
  max-height: 2rem;
  margin: 0.5rem;
}
</style>
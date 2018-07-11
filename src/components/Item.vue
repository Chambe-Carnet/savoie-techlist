<script>
export default {
}
</script>

<template>
  <q-card inline class="q-ma-sm">
  <q-card-media>
    <img src="../assets/logo.png">
  </q-card-media>
  <q-card-title>
    Chambé-Carnet
    <div slot="right" class="row items-center">
      <q-icon name="place" /> 250 ft
    </div>
  </q-card-title>
  <q-card-main>
    <p>Association</p>
    <p class="text-faded">Small plates, salads & sandwiches in an intimate setting.</p>
  </q-card-main>
  <q-card-separator />
  <q-card-actions>
    <q-btn flat round dense icon="event" />
    <q-btn flat label="5:30PM" />
    <q-btn flat label="7:30PM" />
    <q-btn flat label="9:00PM" />
    <q-btn flat color="primary" label="Reserve" />
  </q-card-actions>
</q-card>
</template>

<style scoped>
.q-card-media > img {
 width: 100px;
 height: auto;
}
</style>

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
      <span slot="subtitle">Association</span>
      <q-icon slot="right" name="more_vert">
        <q-popover>
          <q-list link class="no-border">
            <q-item v-close-overlay>
              <q-item-main label="Remove Card" />
            </q-item>
            <q-item v-close-overlay>
              <q-item-main label="Send Feedback" />
            </q-item>
            <q-item v-close-overlay>
              <q-item-main label="Share" />
            </q-item>
          </q-list>
        </q-popover>
      </q-icon>
    </q-card-title>
    <q-card-main>
      <p class="text-faded">Promouvoir le web et contribuer au dynamisme du numérique dans les pays de Savoie, rassembler les acteurs du web pour connecter les ressources</p>
    </q-card-main>
    <q-card-separator />
    <q-card-actions>
      <q-btn flat round dense icon="home" />
      <q-btn flat round dense icon="email" />
      <q-btn flat round dense icon="location_on" />
    </q-card-actions>
  </q-card>
</template>

<style scoped>
.q-card {
  width: 300px;
}
.q-card-media > img {
 width: 100px;
 height: auto;
}
</style>

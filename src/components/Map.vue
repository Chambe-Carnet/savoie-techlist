<script>
import L from 'leaflet'
import 'leaflet/dist/leaflet.css';
export default {
  mounted() {
    var map = L.map(this.$el).setView([45.4947058, 6.5433562], 9);

    L.tileLayer("https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token={accessToken}", {
      attribution:
        '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors',
      id: 'mapbox.light',
      accessToken: 'pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw'
    }).addTo(map);
  }
};
</script>

<template>
  <div class="map"></div>
</template>

<style scoped>
.map {
  width: 100%;
  height: 800px;
}
</style>

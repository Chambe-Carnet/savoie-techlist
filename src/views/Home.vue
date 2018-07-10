<template>
  <q-page class="flex">
    <my-map />
  </q-page>
</template>

<style>
</style>

<script>
import Map from '@/components/Map'
export default {
  components: { 'my-map': Map },
  name: 'PageHome'
}
</script>

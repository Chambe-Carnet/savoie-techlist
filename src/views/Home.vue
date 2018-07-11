<template>
  <q-page class="flex">
    <l-map />
    <item />
  </q-page>
</template>

<style>
</style>

<script>
import Map from '@/components/Map'
import Item from '@/components/Item'

export default {
  components: { 
    'l-map': Map,
    Item
  },
  name: 'PageHome'
}
</script>

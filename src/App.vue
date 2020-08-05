<template>
  <div id="app">
    <Zoom src="https://picsum.photos/1000/1000?image=142" src-large="https://picsum.photos/2000/2000?image=142"/>
  </div>
</template>

<script>
import Zoom from './components/Zoom.vue'

export default {
  name: 'App',
  components: {
    Zoom
  }
}
</script>

<style>
</style>

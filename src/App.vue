<template>
  <img
    alt="Vue logo"
    src="./assets/logo.png"
  />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import G6 from '@antv/g6'

console.log(G6)
export default {
  name: 'App',
  components: {
    HelloWorld
  },
  setup () {
  }
}
</script>

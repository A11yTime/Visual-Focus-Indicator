<template>
  <NativeIndicator />
  <CustomIndicator />
</template>

<script>
import NativeIndicator from './components/NativeIndicator.vue'
import CustomIndicator from './components/CustomIndicator.vue'
export default {
  name: 'App',
  components: {
    NativeIndicator,
    CustomIndicator,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <TheHeader></TheHeader>
    <main>
      <div class="container mt-5">
        <div class="bg-dark text-white pt-5 pb-5 text-start fw-bold">&rArr; Content goes here &lArr;</div>
      </div>
    </main>
    <TheFooter></TheFooter>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheFooter from './components/TheFooter.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    TheFooter,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

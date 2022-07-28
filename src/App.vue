<template>
  <div id="app">
    <div>
      <Header></Header>
      <p1>{{msg}}</p1>
      <Footer></Footer>

    </div>
  </div>
</template>

<script>
import Header from './components/Header/AppHeader.vue'
import Footer from './components/Footer/AppFooter.vue'

export default {
  name: 'app',
  components: {
    Header,
    Footer
  },
  data() {
    return {
      msg: 'hellword！'
    }
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

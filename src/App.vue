<template>
  <div class="container my-1">
    <navbar/>
  <div class="row justify-content-between my-2">
    <links/>
    <bod/>
  </div>
  <foot/>
  </div>
   <br><br><br><br>
   <formm/>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import navbar from './components/navbar.vue'
import bod from './components/bod.vue'
import links from './components/links.vue'
import foot from './components/foot.vue'
import formm from './components/form.vue'


export default {
  name: 'App',
  components: {
   foot,links,bod,navbar,formm
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

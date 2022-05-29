<template>

  <NavbarComponent :msg="msg" :category="category" :description="description" :classModal ="classModal" />
   
</template>

<script>
import NavbarComponent from './components/NavbarComponent'

export default {
  name: 'App',
  components: {
    NavbarComponent
  },

  data(){
  return {
   
   msg: "Shoes",
   category: "Sneakers",
   description: "Thes best Sneakers",
   classModal: "sale"

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

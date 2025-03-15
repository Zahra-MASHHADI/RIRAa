<template>
  <div class="mainPage">

    <HelloWorld/>


  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>

#app , body{
  margin:0;
  padding:0;
}
.mainPage{
  background-color: black;
  height:100vh;
  display: flex;
    justify-items: center;
    align-items: center;
    width: 100%;
}
</style>

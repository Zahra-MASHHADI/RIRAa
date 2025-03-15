<template>
  <div class="mainPage">

    <HelloWorld/>
<!-- dgdg -->

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

.mainPage{
  background-color: black;
  height:100vh;
}
</style>

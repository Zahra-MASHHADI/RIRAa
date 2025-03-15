<template>
  <div class="relative">
    <img src="/Task - Task info.png" />
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
  .relative{
    position: relative;
    width: 100%;
    display:flex;
    justify-content: center;
    align-items: center;
  }
  @media screen and (max-width: 768px) {  
   .relative img{
    width:500px
   }
}  
</style>

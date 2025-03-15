<template>
  <div class="relative">
    <div class="hello">
    coming soon...

    </div>
    <div class="circle">

    </div>
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
  .hello{
    color:rgb(248, 246, 246) ;
    font-size: 60px;
    text-align: center;
    width:100%;
    position: relative;
    z-index: 2;
  }
  .circle{
    width:200px;
    height:200px;
    background-color:rgb(160, 2, 2) ;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-50%);
    border-radius: 50%;
    z-index: 1;
  }
  .relative{
    position: relative;
    width: 100%;
  }
</style>

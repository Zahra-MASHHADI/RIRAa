<template>
  <div class="relative ">
    <div class="mobile">
    <img src="/Frame.png" />
    </div>
    <div class="content">
      <img src="/group4005.png" />  
    </div>
    <div class="desktop">
    <img src="/Frame.png" />
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
  
  .relative{
    position: relative;
    width: 100%;
    display:flex;
    justify-content: center;
    align-items: center;
    gap:20px;
  }
  .relative .mobile{

    display:none;

  }
  @media screen and (max-width: 768px) {  
  
   .relative{
    /* width:100%; */
    flex-wrap: wrap;
   }
   .relative .content{
    width:85  %
   }
   .relative div img{
    width:100%
   }
   .relative .mobile{

    display:block;

    }
    .relative .desktop{

    display:none;

    }
 
}  
</style>

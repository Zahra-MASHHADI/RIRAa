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
    <div class="telephone">
      <a href="tel:02142591">
         +۹۸۲۱-۴۲۵۹۱
      </a>
          <svg width="15" height="15" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M2.25 6.75C2.25 15.0343 8.96573 21.75 17.25 21.75H19.5C20.7426 21.75 21.75 20.7426 21.75 19.5V18.1284C21.75 17.6121 21.3987 17.1622 20.8979 17.037L16.4747 15.9312C16.0355 15.8214 15.5734 15.9855 15.3018 16.3476L14.3316 17.6412C14.05 18.0166 13.563 18.1827 13.1223 18.0212C9.81539 16.8098 7.19015 14.1846 5.97876 10.8777C5.81734 10.437 5.98336 9.94998 6.3588 9.6684L7.65242 8.69818C8.01453 8.4266 8.17861 7.96445 8.06883 7.52533L6.96304 3.10215C6.83783 2.60133 6.38785 2.25 5.87163 2.25H4.5C3.25736 2.25 2.25 3.25736 2.25 4.5V6.75Z" stroke="#ABAEB0" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>

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
  .telephone{
    background-color: #F5F5F5;
    position: absolute;
    bottom: 40px;
    left:51%;
    color: gray;
    display:flex;
    gap:10px;
    align-items: center;
    font-size:24px
  }
  .telephone a{
    text-decoration: none;
    text-decoration-line: none;
    color: gray;
  }
  .relative{
    padding: 10px;
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
   .relative .content img{
    width:90%
   }
   .relative .mobile img{
    width:70%;

   }
   .relative .mobile{
    text-align: center;
    margin-bottom: 40px;
    display:block;

    }
    .relative .desktop{

    display:none;

    }
    .telephone{
    
    bottom: 20px;
    right:0px;
    font-size:15px

  }

 
}  
</style>

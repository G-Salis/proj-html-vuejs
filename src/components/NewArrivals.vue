<template>
   <section class="new-arrivals">


    <div class="na-ctn">

          <div class="na-title">
       <div class="line"></div>

       <div class="title">
         
         New arrivals
       </div>

       <div class="line"></div>
    </div>

     <div class="na-subtitle">
       Most have product from our top seller
     </div>
      
    </div>

     
     

    <div class="na-clothing">

     

      <div class="na-chose">

        
        <img src="../assets/img/black_elegant_leather_jacket-400x520.jpg" alt="">

        <div class="na-btn-left"><i class="fas fa-chevron-left"></i></div>
        
      
      </div>

      <div class="na-chose">

         <img src="../assets/img/hipster_black_top-400x520.jpg" alt="">
       
      </div>

      <div class="na-chose">

        <img src="../assets/img/black_leather_jacket-400x520.jpg" alt="">
       

      </div>

       <div class="na-chose">

        <img src="../assets/img/spring_printed_dress-400x520.jpg" alt="">
       
      </div>

      <div class="na-chose">

       

        <img src="../assets/img/modern_love_tee-400x520.jpg" alt="">

          <div class="na-btn-right"><i class="fas fa-chevron-right"></i></div>
       

      </div>

   

      
      
     
    </div>


  </section>
</template>

<script>


export default {
  name: 'NewArrivals',
 
}
</script>

<style lang="scss">
.new-arrivals{
  min-height: 200px;
 
}

.na-ctn{
  width: 85%;
  margin: 50px auto;
}

.na-title{
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.na-subtitle{
  color: grey;
  text-align: center;
  
}

.na-buttons{
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 25px;
  color: black;
}

.na-btn{
  font-weight: 600;
  padding: 10px 30px;
  background-color: #F6F6F6;
  border: 1px solid gray;
}

.na-btn:hover{
  font-weight: 600;
  padding: 10px 30px;
  background-color: white;
  border: 1px solid gray;
}

.na-clothing{
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px 0px;
}

.na-chose{
  position: relative;
  width: calc(100% / 5);

  img{
    width: 100%;
  }

  .na-btn-left{
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    bottom: 100px;
    background-color: lightgray;
    width: 30px;
    height: 70px;
  }

  .na-btn-right{
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    bottom: 100px;
    right: 0;
    background-color: lightgray;
    width: 30px;
    height: 70px;
  }

}
</style>
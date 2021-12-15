<template>
  <section class="best-seller">

    <div class="bs-title">
       <div class="line"></div>

       <div class="title">
         Best Seller
       </div>

       <div class="line"></div>
     </div>

     <div class="bs-subtitle">
       Most have product from our top seller
     </div>
     
     

    <div class="bs-clothing">

     

      <div class="bs-chose">

        <img src="../assets/img/spring_printed_dress-200x260.jpg" alt="">

        <div class="bs-btn-left"><i class="fas fa-chevron-left"></i></div>
      
      </div>

      <div class="bs-chose">

        <img src="../assets/img/modern_love_tee-200x260.jpg" alt="">
       
      </div>

      <div class="bs-chose">

        <img src="../assets/img/black_leather_jacket-200x260.jpg" alt="">
       

      </div>

       <div class="bs-chose">

        <img src="../assets/img/black_elegant_leather_jacket-200x260.jpg" alt="">
       
      </div>

      <div class="bs-chose">

        <img src="../assets/img/hipster_black_top-200x260.jpg" alt="">

          <div class="bs-btn-right"><i class="fas fa-chevron-right"></i></div>
       

      </div>

   

      
      
     
    </div>

  </section>
</template>

<script>


export default {
  name: 'BestSeller',
 
}
</script>

<style lang="scss">
.best-seller{
  color: white;
  min-height: 200px;
  width: 85%;
  margin: 50px auto;
}

.bs-title{
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.bs-subtitle{
  color: grey;
  text-align: center;
  
}

.bs-buttons{
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 25px;
  color: black;
}

.bs-btn{
  font-weight: 600;
  padding: 10px 30px;
  background-color: #F6F6F6;
  border: 1px solid gray;
}

.bs-btn:hover{
  font-weight: 600;
  padding: 10px 30px;
  background-color: white;
  border: 1px solid gray;
}

.bs-clothing{
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px 0px;
}

.bs-chose{
  position: relative;

  .bs-btn-left{
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    bottom: 100px;
    background-color: lightgray;
    width: 30px;
    height: 70px;
  }

  .bs-btn-right{
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




@import "../assets/style/utilities.scss";
</style>
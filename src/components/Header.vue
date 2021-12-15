<template>

<section class="header">

  <div class="hdr">


       <div class="ctn-left">

          <div class="hdr-social">
            <i class="fab fa-facebook-f"></i>
            <i class="fab fa-twitter"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-youtube"></i>
          </div>

       <span>Shopping Card</span>

      </div>
 
       
     
     <div class="ctn-center">

       <div class="hdr-account">
          My Account <i class="fas fa-chevron-down"></i>
       </div>

     </div>

     <div class="ctn-right">

       <div class="hdr-cart">
          <i class="fas fa-shopping-cart"></i> CART <i class="fas fa-chevron-down"></i>
       </div>

     </div>

     

  </div>

  <div class="hdr">


       <div class="ctn-logo">

          <div class="hdr-img">
            <img src="../assets/img/classic_shop_logo1x.png" alt="">
          </div>

      </div>     

        <div class="ctn-nav">

          <div class="hdr-list">

            <span>Home<i class="fas fa-chevron-down"></i></span>
            <span>Shop<i class="fas fa-chevron-down"></i></span>
            <span>Product<i class="fas fa-chevron-down"></i></span>
            <span>Categories<i class="fas fa-chevron-down"></i></span>
            <span>News</span>
            <span>Elements<i class="fas fa-chevron-down"></i></span>
            <span class="btn-blue">SHOP NOW!</span>
            <span><i class="fas fa-search"></i></span>
            
          </div>

      </div> 

  </div>

</section>

   

  
  
</template>

<script>


export default {
  name: 'Header',
 
}
</script>

<style lang="scss">

.header{
  text-align: center;
}

i{
  font-size: 12px;
  padding-left: 5px;
}

.hdr{
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #64686C !important;
  border-bottom: 1px solid #A0A5A5;
  height: 80px;
}

.ctn-left{
  display: flex;
  justify-content: space-between;
  width: 60%;
  margin-left: 7.5%;
  height: 80px;
  line-height: 80px;


  span{
    text-align: right;
    padding-right: 5px;
  }
  
}

.hdr-social{
  display: inline-block;
  text-align: left;
  
}


.hdr-social i{
  margin-right: 20px;
  font-size: 20px;
}

.ctn-center, .ctn-right{
  width: 15%;
  height: 80px;
  line-height: 80px;
}


.ctn-center, .ctn-left{
  border-right: 1px solid #A0A5A5;
}

.ctn-right{
  margin-right: 7.5%;
}


p, span, .hdr-account, .hdr-cart{
  font-weight: 900;
}


.ctn-logo{
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-left: 7.5%;
  height: 80px;
}


.hdr-list span{
  padding: 5px 15px;
}


  @import "../assets/style/utilities.scss";
</style>
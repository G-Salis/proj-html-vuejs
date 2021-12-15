<template>
  <section class="sales">

    <div class="sl-cnt">
      <div class="sl-photo1">

    
        <div class="sl-title">70% Off</div>
        <div class="sl-subtitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</div>
        <span class="btn-white">View More</span>
      

      </div>
      <div class="sl-photo2">

        <div class="sl-title">Free Shipping</div>
        <div class="sl-subtitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</div>
        <span class="btn-white">View More</span>
        
      </div>
    </div>

  </section>
</template>

<script>


export default {
  name: 'Sales',
 
}
</script>

<style lang="scss">
.sales{
  background-image: url('../assets/img//bkgd_confetti-compressor.jpg');
  background-position: center;
  min-height: 400px;
  width: 100%;
  color: white;
}

.sl-cnt{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 85%;
  margin: 0 auto;
}

.sl-photo1{
  width: 50%;
  margin: 40px;
  height: 500px;
  background-image: url('../assets/img/promo_box_1_bg.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding-left: 70px;
}

.sl-photo2{
  width: 50%;
  margin: 40px;
  height: 500px;
  background-image: url('../assets/img/promo_box_2_bg.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding-left: 70px;
}

.sl-title{
  font-size: 40px;
}
.sl-subtitle{
  font-size: 14px;
  text-transform: uppercase;
  margin-bottom: 15px;
}
</style>
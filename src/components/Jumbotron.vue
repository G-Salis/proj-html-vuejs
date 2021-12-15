<template>
   <section class="jumbotron">

     <div class="jbt">
       <div class="jbt-title">Brand New Arrivals</div>
       <div class="jbt-subtitle">New Collection From New York</div>
       <span class="btn-white">View All</span>
       <span class="btn-white">LookBook</span>
     </div>

  </section>
</template>

<script>


export default {
  name: 'Jumbotron',
 
}
</script>

<style lang="scss">

.jumbotron{
  background-image: url('../assets/img/home1_slide_three_bg_2.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
  height: 592px;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  }

  .jbt{
    color: white;
  }

  .jbt-title{
    font-size: 100px;
  }
  .jbt-subtitle{
    font-size: 40px;
    text-transform: uppercase;
    margin-bottom: 15px;
  }

    @import "../assets/style/utilities.scss";
</style>
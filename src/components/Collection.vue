<template>

<section class="collection">

  <div class="cln">
    <div class="cln-poster photo-1">
       <div class="cln-title">Winter Collection</div>
       <div class="cln-subtitle">Stylish and warm</div>
       <span class="btn-white">View More</span>
    </div>
    <div class="cln-poster photo-2">
      <div class="cln-title">Spring Collection</div>
      <div class="cln-subtitle">Bright and colorful</div>
      <span class="btn-white">View More</span>
    </div>
    <div class="cln-poster photo-3">
      <div class="cln-title">Autumn Collection</div>
      <div class="cln-subtitle">Rich and comfortable</div>
      <span class="btn-white">View More</span>
    </div>
  </div>

</section>
  
</template>

<script>


export default {
  name: 'Collection',
 
}
</script>

<style lang="scss">
.collection{
  background-color: rgb(223, 177, 78);
  min-height: 200px;
  width: 100%;
}

.cln{
  display: flex;
  color: white;

}

.cln-poster{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: end;
  width: calc(100% / 3);
  min-height: 616px;
  padding-bottom: 70px;

}

.photo-1{
  background-image: url('../assets/img//winter_collection_bg.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;   
}
.photo-2{
  background-image: url('../assets/img/spring_collection_bg.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;  

}
.photo-3{
  background-image: url('../assets/img/autumn_collection_bg.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;  
}

.cln-title{
  font-size: 40px;
}
.cln-subtitle{
  font-size: 14px;
  text-transform: uppercase;
  margin-bottom: 15px;
}

    @import "../assets/style/utilities.scss";
</style>
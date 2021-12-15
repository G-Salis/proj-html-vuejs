<template>
   <section class="feedback">

     <div class="fb-photo">
       <img src="../assets/img/man_testimonial.png" alt="">
     </div>

     <div class="fb-text">
       Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt dicta nulla ipsa incidunt molestiae repudiandae enim, earum quam distinctio quaerat, id, excepturi labore hic? Sit fugit voluptatum provident officia ipsa.
     </div>

     <div class="fb-gen">

       <span class="fb-name">
        Dario Pineda,
       </span>

       <span class="fb-acquist">
        Theme Fusion
       </span>
       
     </div>

     <div class="fb-gen">

       <span class="fb-name">
        <i class="fas fa-circle"></i>
       </span>

       <span class="fb-acquist">
        <i class="far fa-circle"></i>
       </span>
       
     </div>
     

  </section>
</template>

<script>


export default {
  name: 'Feedback',
 
}
</script>

<style lang="scss">
.feedback{
  background-image: url('../assets/img/testimonials_home_1_bg.jpg');
  background-position: center;
  background-size: contain;
  height: 500px;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}

.fb-photo{
  width: 60px;
  img{
    width: 100%;
  }
}

.fb-text{
  width: 65%;
  font-style: oblique;
}

.fb-gen{
  margin: 30px;
}

.fb-acquist{
  font-weight: 400;
}
</style>
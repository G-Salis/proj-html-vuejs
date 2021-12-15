<template>
   <section class="featured">

     <div class="ft-title">
       <div class="line"></div>

       <div class="title">
         Featured Product
       </div>

       <div class="line"></div>
     </div>

     <div class="ft-subtitle">
       Most have product from our top seller
     </div>
     
     <div class="ft-buttons">
       <div class="ft-btn">Man</div>
       <div class="ft-btn">Woman</div>
       <div class="ft-btn">Accessories</div>
     </div>

    <div class="ft-clothing">
      <div class="ft-chose">

        <img src="../assets/img/black_elegant_leather_jacket-400x520.jpg" alt="">
        <ul>
          <li>
            <div class="ft-name-clothing">
              Black Leather Jacket
            </div>
          </li>
          <li>
            <div class="ft-tag-clothing">
              Man,Jacket,Jeans
            </div>
          </li>
          <li>
            <span class="ft-sale-clothing">
              $235
            </span>
            <span class="ft-price-clothing">
              $200
            </span>
          </li>
        </ul>

      </div>

      <div class="ft-chose">

        <img src="../assets/img/black_leather_suit-400x520.jpg" alt="">
        <ul>
            <li>
              <div class="ft-name-clothing">
                Black Leather Suit
              </div>
            </li>
            <li>
              <div class="ft-tag-clothing">
                Man,Jacket
              </div>
            </li>
            <li>
              <span class="ft-price-clothing">
                $176
              </span>
            </li>
          </ul>

      </div>

      <div class="ft-chose">

        <img src="../assets/img/blue_jacket_and_white_stripe_tee-400x520.jpg" alt="">
        <ul>
            <li>
              <div class="ft-name-clothing">
                Blue Jacket & Stripe Tee
              </div>
            </li>
            <li>
              <div class="ft-tag-clothing">
                Man,Jacket,Suit
              </div>
            </li>
            <li>
              <span class="ft-price-clothing">
                $580
              </span>
            </li>
          </ul>

      </div>

      <div class="ft-chose">

        <img src="../assets/img/blue_leather_jacket-400x520.jpg" alt="">
        <ul>
          <li>
            <div class="ft-name-clothing">
              Modern Black Leather Suit
            </div>
          </li>
          <li>
            <div class="ft-tag-clothing">
              Man,Jacket
            </div>
          </li>
          <li>
            <span class="ft-price-clothing">
              $96
            </span>
          </li>
        </ul>

      </div>
      
     
    </div>
    

  </section>
</template>

<script>


export default {
  name: 'Featured',
 
}
</script>

<style lang="scss">
.featured{
  color: white;
  min-height: 200px;
  width: 85%;
  margin: 50px auto;
}

.ft-title{
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.ft-subtitle{
  color: grey;
  text-align: center;
  
}

.ft-buttons{
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 25px;
  color: black;
}

.ft-btn{
  font-weight: 600;
  padding: 10px 30px;
  background-color: #F6F6F6;
  border: 1px solid gray;
}

.ft-btn:hover{
  font-weight: 600;
  padding: 10px 30px;
  background-color: white;
  border: 1px solid gray;
}

.ft-clothing{
  display: flex;
  align-items: center;
  justify-content: center;
}

.ft-chose{
   width: calc(100% / 4);
   img{
     width: 100%;
   }
}

ul{
  color: black;
  list-style: none;
}

li{
  margin: 10px 0px;
}

.ft-name-clothing{
  font-size: 12px;
  font-weight: 600;
}

.ft-tag-clothing{
  font-size: 10px;
}

.ft-sale-clothing{
  text-decoration: line-through;
  font-size: 10px;
}

.ft-price-clothing{
  padding-left: 3px;
}

.ft-sale-clothing, .ft-price-clothing{
  color: #427ED5;
}

@import "../assets/style/utilities.scss";
</style>
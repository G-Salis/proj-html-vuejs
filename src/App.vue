<template>
 <div id="app">

    <Header/>
    <Jumbotron/>
    <Featured/>
    <Collection/>
    <BestSeller/>
    <Sales/>
    <NewArrivals/>
    <Feedback/>
    <Blog/>
    <BrandLogo/>
    <Subscribe/>
    <Footer/>
  
  </div>
  
</template>

<script>
import Header from "./components/Header.vue"
import Jumbotron from "./components/Jumbotron.vue"
import Featured from "./components/Featured.vue"
import Collection from "./components/Collection.vue"
import BestSeller from "./components/BestSeller.vue"
import Sales from "./components/Sales.vue"
import NewArrivals from "./components/NewArrivals.vue"
import Feedback from "./components/Feedback.vue"
import Blog from "./components/Blog.vue"
import BrandLogo from "./components/BrandLogo.vue"
import Subscribe from "./components/Subscribe.vue"
import Footer from "./components/Footer.vue"
import Sales from './components/Sales.vue'



export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Featured,
    Collection,
    BestSeller,
    Sales,
    NewArrivals,
    Feedback,
    Blog,
    BrandLogo,
    Subscribe,
    Footer,
  }
 
}
</script>

<style lang="scss">

  @import "./assets/style/generals.scss";
  @import "./assets/style/utilities.scss";

</style>

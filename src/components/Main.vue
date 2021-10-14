<template>
  <div class="container-fluid">
      <div class="row">
        <div class="col-12 text-center">
          <p>
            WE HAVE YOU COVERED
          </p>
          <h2>
            Avada Grooming Products
          </h2>
        </div>
      </div>
      <div class="row">
        <Product v-for="(prod,index) in products" :key="index" :prod="prod"/>
      </div>
      <div class="row">
        <div class="col-12 text-center">
          <button class="button_gold">SHOP OUR PRODUCT RANGE</button>
        </div>
      </div>
  </div>
</template>

<script>
import Product from "./Product.vue"
export default {
  name:"Main",
  components:{
     Product,
  },
  data(){
    return{
      products:[
        {
          img:require("../assets/img/brush_dark-400x400.png"),
          title:"Brush",
          price:"$15.00"
        },
        {
          img:require("../assets/img/scissors-400x400.png"),
          title:"Scissors",
          price:"$85.00"
        },
        {
          img:require("../assets/img/hot_oil_dark-400x400.png"),
          title:"Hot Oil",
          price:"$15.00"
        },
        {
          img:require("../assets/img/straight_razor_dark-400x400.png"),
          title:"Straight Razor",
          price:"$30.00"
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
  background-image: url(../assets/img/avadabarbers-reviewsbackground.jpg);
  background-position: top;
  margin-top: 6.25rem;
  padding-top: 13rem;
}
p{
  color: $base_color;
  font-size: 1rem;
}
h2{
  color: $secondary_color;
  font-size: 4rem;
  font-weight: bold;
}
h4{
  color: $base_color;
}
button{
margin-bottom: 12.5rem;
}
</style>
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
        <div class="col-3 text-center">
          <img src="../assets/img/brush_dark-400x400.png" alt="">
          <h4>Brush</h4>
          <p>$15.00</p>
        </div>
        <div class="col-3 text-center">
          <img src="../assets/img/scissors-400x400.png" alt="">
          <h4>Scissors</h4>
          <p>$85.00</p>
        </div>
        <div class="col-3 text-center">
          <img src="../assets/img/hot_oil_dark-400x400.png" alt="">
          <h4>Hot Oil</h4>
          <p>$15.00</p>
        </div>
        <div class="col-3 text-center">
          <img src="../assets/img/straight_razor_dark-400x400.png" alt="">
          <h4>Straight Razor</h4>
          <p>$30.00</p>
        </div>
      </div>
      <div class="row">
        <div class="col-12 text-center">
          <button class="button_gold">SHOP OUR PRODUCT RANGE</button>
        </div>
      </div>
  </div>
</template>

<script>
export default {

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
</style>
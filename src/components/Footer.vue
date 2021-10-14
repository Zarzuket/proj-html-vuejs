<template>
  <div class="container-fluid">
    <div class="container centered">
      <div class="row">
        <div class="col-4 text-center">
          <img src="../assets/img/avadabarbers_footer_shop_image-400x312.png" alt="">
          <button class="button_gold">SHOP OUR RANGE NOW</button>
        </div>
        <div class="col-4">
          <div class="row">
            <div class="col-12 text-center">
              <img src="../assets/img/avadabarbers-logo-x2-200x70.png" alt="">
            </div>
          </div>
          <div class="row">
            <div class="col-12 text-center mt-5">
              <ul>
                <li>Avadaba Barbers</li>
                <li>123 New York Street</li>
                <li>New York City</li>
                <li>info@yourwebsite.com</li>
                <li>+1 (555)555-1212)</li>
              </ul>
            </div>
          </div>
          <div class="row">
            <div class="col-12 text-center mt-3">
              <h5>FOLLOW US</h5>
            </div>
          </div>
          <div class="row">
            <div class="col-12 text-center mt-3">
              <a href="#">
              <i class="fab fa-facebook-f"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-youtube"></i>
              <i class="fab fa-instagram-square"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="col-4 text-center">
          <img src="../assets/img/avadabarbers_footer_appointment_image-400x312.png" alt="">
          <button class="button_gold">BOOK YOUR APPOINTMENT</button>
        </div>
      </div>
    </div>
    <div class="container-fluid other_black d-flex align-items-center justify-content-center">
      <div class="row">
        <div class="col-12 text-center ">
          <p>© Copyright 2012-2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
}
</script>

<style lang="scss" scoped>
  @import "../assets/common.scss";
.container-fluid{
  background-color: #121314;
  // height: 12.5rem;
}
.centered{
  height: 500px;
  padding: 50px;
}
H5{
  color: $base_color;
}
.p10{
  padding: .625rem;
}
li{
  list-style: none;
  color: grey;
}
i{
  color: white;
  padding: 0 .5875rem;
}
.other_black{
  background-color: #161718;
  height: 4.875rem;
}
</style>
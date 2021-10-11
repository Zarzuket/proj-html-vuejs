<template>
  <div>
      <!-- <h1>{{title}}</h1> -->
      <div class="container-fluid">
          <div class="container">
              <nav class="d-flex justify-content-between align-items-center">
                  <div class="logo">
                      <img src="../assets/img/avadabarbers-logo-x2-200x70.png" alt="">
                  </div>
                  <div>
                      <i class="fas fa-shopping-cart"></i>
                      <i class="fas fa-bars"></i>
                  </div>
              </nav>
            <div class="container">
                <div class="row">
                    <div class="col-6 d-flex flex-column align-items-center justify-content-center">
                        <h1>Barber Shop</h1>
                        <hr>
                        <p>The pinnacle of Male Grooving</p>
                        <button class="button_gold">LEARN MORE</button>
                    </div>
                    <div class="col-6">
                        <img src="../assets/img/avadabarbers_hero_focalmirror-600x825.png" alt="">
                    </div>
                </div>
            </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Header",
    // props: ["title"]
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
    background-image: url(../assets/img/avadabarbers-hero-bg.jpg);
}


nav{
    i{
        color: white;
        padding: 0 0.8rem;
    }
}
h1{
    color: white;
    font-size: 6.25rem;
    margin-right: auto;
}
hr{
    color: $base_color;
    width: 15.5rem;
    margin-right:auto;
    height: 3.25rem;
    opacity: 1;
}
p{
    padding: 1.25rem 0;
    margin-right:auto;
    font-size: 1.25rem;
    color: grey;
}
button{
    margin-right: auto;
}

</style>
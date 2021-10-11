<template>
  <div>
      <!-- <h1>{{title}}</h1> -->
      <div class="container-fluid">
          <div class="container">
              <nav>
                  <div class="logo">
                      <img src="../assets/img/avadabarbers-logo-x2-200x70.png" alt="">
                  </div>
                  <div>
                      <i class="fas fa-bars"></i>
                      <i class="fas fa-shopping-cart"></i>
                  </div>
              </nav>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Header",
    props: ["title"]
}
</script>

<style lang="scss" scoped>
.container-fluid{
    background-image: url(../assets/img/avadabarbers-hero-bg.jpg);
}
</style>
<template>
  <div>
      <div class="container-fluid">
          <div class="row">
              <div class="col-12 text-center">
                  <p>AWARD WINNING</p>
                  <h3>Pro Barbers</h3>
                  <button class="button_gold">MEET YOUR NEW BARBER</button>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "SectionAward"

}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
    padding: 10.125rem 0;
    height: 50vh;
    background-image: url(../assets/img/avadabarbers-about-introbackground.jpg);
    background-repeat: repeat;
}
h3{
    color: $secondary_color;
    font-size: 3.125rem;
    font-weight: bold;
}
p{
    color: $base_color;
    font-weight: bold;
    letter-spacing: .125rem
}
</style>
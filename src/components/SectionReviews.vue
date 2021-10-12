<template>
  <div class="container-fluid">
      <div class="row">
          <div class="col-12 text-center">
              <p>WHAT PEOPLE SAY</p>
              <h3>Reviews</h3>
          </div>
      </div>
      <div class="container d-flex">
        <div class="col-4 text-center">
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi sit dolores delectus. Esse ea tempora ipsam, molestias consectetur qui? Ea, nemo? Dolorum ea blanditiis aliquid tempore necessitatibus eveniet ipsa architecto.</p>
          <img class="img_reviews" src="../assets/img/avadabarbers-trimcut-gallery6-200x200.jpg" alt="John Doe">
          <h5>John Doe</h5>
        </div>
        <div class="col-4 text-center">
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi sit dolores delectus. Esse ea tempora ipsam, molestias consectetur qui? Ea, nemo? Dolorum ea blanditiis aliquid tempore necessitatibus eveniet ipsa architecto.</p>
          <img class="img_reviews" src="../assets/img/avadabarbers-trimcut-gallery7-200x201.jpg" alt="Pete Jones">
          <h5>Pete Jones</h5>
        </div>
        <div class="col-4 text-center">
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi sit dolores delectus. Esse ea tempora ipsam, molestias consectetur qui? Ea, nemo? Dolorum ea blanditiis aliquid tempore necessitatibus eveniet ipsa architecto.</p>
          <img class="img_reviews" src="../assets/img/avadabarbers-trimcut-gallery3-200x201.jpg" alt="Mark Wilson">
          <h5>Mark Wilson</h5>
        </div>
      </div>
  </div>
</template>

<script>
export default {
name: "SectionReviews"
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
  margin-top: 10.125rem;
}
.col-12{
  p{
    color: $base_color;
    font-weight: bold;
    letter-spacing: .125rem
    }
    h3{
      margin-bottom: 5.5rem;
    }
}
h3{
  color: $secondary_color;
  font-size: 5.125rem;
  font-weight: bold;
}
.img_reviews{
  border-radius: 50%;
  width: 30%;
  padding: 1.25rem 0rem;
}
.col-4{
  p{
    padding: 0rem 5.25rem;
    color: grey;
  }
  h5{
    color: $base_color;
  }
}

</style>
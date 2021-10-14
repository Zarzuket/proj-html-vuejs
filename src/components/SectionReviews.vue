<template>
  <div class="container-fluid">
    <div class="container absolute">
      <div class="row text-center">
        <div class="col-5 px-0">
          <img src="../assets/img/shaving_butter-200x200.png" alt="">
        </div>
        <div class="col-7 d-flex flex-column text-center align-item-center justify-content-center">
          <h5>THIS MONTHS FEATURED PRODUCT</h5>
          <h3>Shaving Butter</h3>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iure molestiae laborum rem nesciunt labore. Impedit veritatis inventore mollitia, aliquid adipisci quis magnam recusandae odio, sunt deserunt iste aspernatur ipsa fugiat.</p>
          <button class="button_gold">BUY NOW</button>
        </div>
      </div>
    </div>
    <div class="row">
        <div class="col-12 text-center">
            <p>WHAT PEOPLE SAY</p>
            <h3>Reviews</h3>
        </div>
    </div>
    <div class="container d-flex">
      <Card v-for="(author, index) in authors" :key="index" :xxx="author"/>
    </div>
  </div>
</template>

<script>
import Card from "./Card.vue"
export default {
name: "SectionReviews",
components:{
  Card
},
data(){
  return{
    authors:[
      {
        p:"Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi sit dolores delectus. Esse ea tempora ipsam, molestias consectetur qui?",
        img:require("../assets/img/avadabarbers-trimcut-gallery6-200x200.jpg"),
        name:"John Doe"
      },
      {
        p:"Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi sit dolores delectus. Esse ea tempora ipsam, molestias consectetur qui?",
        img:require("../assets/img/avadabarbers-trimcut-gallery7-200x201.jpg"),
        name:"Pete Jones"
      },
      {
        p:"Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi sit dolores delectus. Esse ea tempora ipsam, molestias consectetur qui?",
        img:require("../assets/img/avadabarbers-trimcut-gallery3-200x201.jpg"),
        name:"Mark Wilson"
      },
    ]
  }
}
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
  margin-top: 30.125rem;
  position: relative;
}
.relative{
  position: relative;
}
.absolute {
  position: absolute;
  top: -40%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.col-5{
  border-top: 4px solid $base_color;
  position: relative;
  img{
  background-image: url(../assets/img/avadabarbers-cta-background.jpg);
  background-position: cover;
  width: 100%;
  };
}

.col-7{
  border-top: 4px solid $base_color;
  background-color: #121413;
  padding: 100px;
  h5{
    color: $base_color;
  }
  p{
    color: grey;
    font-weight: bold;
    letter-spacing: .165rem;
  }
  button{
  margin-right: auto;
  }
}


.col-12{
  margin-top: 6.25rem;
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


</style>
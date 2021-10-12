<template>
  <div class="container-fluid">
      <div class="row">
          <div class="col-12 text-center">
              <p>TALES FROM THE BARBER SHOP</p>
              <h3>Recent Blog Posts</h3>
          </div>
      </div>
      <div class="container d-flex">
          <div class="col-4 text-center">
            <img src="../assets/img/avadabarbers-second-blog-320x202.jpg" alt="Avada Barbers Shop">
            <h4>Avada Barbers Now Open</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque mollitia fugit quos aliquid quia, ipsa quis, quod odit reprehenderit nesciunt quam harum voluptas magni rem perferendis delectus porro ad praesentium!</p>
          </div>
          <div class="col-4 text-center">
            <img src="../assets/img/avadabarbers-choosing-blog-320x202.jpg" alt="AvadaBarbers Chair">
            <h4>Choosing The Right Barber</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque mollitia fugit quos aliquid quia, ipsa quis, quod odit reprehenderit nesciunt quam harum voluptas magni rem perferendis delectus porro ad praesentium!</p>  
          </div>
          <div class="col-4 text-center">
            <img src="../assets/img/avadabarbers-ourservice-blog-320x202.jpg" alt="Avada Barbers at Work">
            <h4>Qick Service Guide</h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque mollitia fugit quos aliquid quia, ipsa quis, quod odit reprehenderit nesciunt quam harum voluptas magni rem perferendis delectus porro ad praesentium!</p>
          </div>
      </div>
      <div class="row mt-5">
          <div class="col-12 text-center">
              <button class="button_gold">READ MORE FROM OUR BLOG</button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "RecentBlog"
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
    margin-top: 14rem;
}
.col-12{
    p{
    color: $base_color;
    font-weight: bold;
    letter-spacing: .125rem
    }
}
h3{
    color: $secondary_color;
    font-size: 4.125rem;
    font-weight: bold;
    margin-bottom: 4.375rem;
}
h4{
    color: $base_color;
}
p{
    color: grey;
    padding: 0 1.5rem;
}
</style>
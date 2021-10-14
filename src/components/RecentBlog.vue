<template>
  <div class="container-fluid">
      <div class="row">
          <div class="col-12 text-center">
              <p>TALES FROM THE BARBER SHOP</p>
              <h3>Recent Blog Posts</h3>
          </div>
      </div>
      <div class="container d-flex">
          <Post v-for="(blog,index) in blog" :key="index" :info="blog"/>
      </div>
      <div class="row mt-5">
          <div class="col-12 text-center">
              <button class="button_gold">READ MORE FROM OUR BLOG</button>
          </div>
      </div>
  </div>
</template>

<script>
import Post from "./Post.vue"
export default {
    name: "RecentBlog",
    components:{
        Post,
    },
    data(){
        return{
            blog:[
                {
                    img:require("../assets/img/avadabarbers-second-blog-320x202.jpg"),
                    title:"Avada Barbers Now Open",
                    post:"Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque mollitia fugit quos aliquid quia, ipsa quis, quod odit reprehenderit nesciunt quam harum voluptas magni rem perferendis delectus porro ad praesentium!"
                },
                {
                    img:require("../assets/img/avadabarbers-choosing-blog-320x202.jpg"),
                    title:"Choosing The Right Barber",
                    post:"Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque mollitia fugit quos aliquid quia, ipsa quis, quod odit reprehenderit nesciunt quam harum voluptas magni rem perferendis delectus porro ad praesentium!"
                },
                {
                    img:require("../assets/img/avadabarbers-ourservice-blog-320x202.jpg"),
                    title:"Qick Service Guide",
                    post:"Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque mollitia fugit quos aliquid quia, ipsa quis, quod odit reprehenderit nesciunt quam harum voluptas magni rem perferendis delectus porro ad praesentium!"
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
    margin: 14rem 0rem;
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
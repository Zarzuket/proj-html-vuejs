<template>
  <div class="col-4 text-center">
    <a href="#">
        <img :src="info.img" :alt="info.title">
        <h4>{{info.title}}</h4>
        <p>{{info.post}}</p>
    </a>
  </div>
</template>

<script>
export default {
    name: "Post",
    props:["info"]
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
h4{
 color: $base_color;
}
p{
  color: grey;
}
</style>
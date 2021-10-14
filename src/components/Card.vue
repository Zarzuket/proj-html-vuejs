<template>
    <div class="col-4 text-center">
        <p>{{xxx.p}}</p>
        <a href="#">
            <img class="img_reviews" :src="xxx.img" :alt="xxx.name">
            <h5>{{xxx.name}}</h5>
        </a>
    </div>
</template>

<script>
export default {
name:"Card",
props:["xxx"]
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
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
<template>  
    <div class="col-3 text-center">
        <a href="#">
            <img :src="prod.img" :alt="prod.title">
            <h4>{{prod.title}}</h4>
            <p>{{prod.price}}</p>
        </a>
    </div>
</template>

<script>
export default {
    name:"product",
    props:["prod"]
}
</script>

<style lang="scss" scoped>

</style>
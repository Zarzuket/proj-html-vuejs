<template>
    <div>
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 text-center">
                    <p>MENS GROOMING</p>
                    <h3>Services</h3>
                </div>
            </div>
            <div class="container text-center">
                <div class="row">
                    <div class="col-4">
                            <img class="img_service" src="../assets/img/avadabarbers-trimcut-icon-before.png" alt="">
                        <h5>
                            Trim & Cut
                        </h5>
                        <p class="info">
                            Avada Barbers are experts in the lickety split trim and hair cut. quick but careful and ridiculously good looking.
                        </p>
                    </div>
                    <div class="col-4">
                        <img class="img_service_2" src="../assets/img/avadabarbers-washndry-icon.png" alt="">
                        <h5>
                            Wash & Dry
                        </h5>
                        <div>
                            <p class="info">
                                Take a seat in our fine leather chairs, lean back and let us lather you a fresh head in a lucurious fashion.
                            </p>
                        </div>
                    </div>
                    <div class="col-4">
                        <img class="img_service" src="../assets/img/avadabarbers-beardtrim-icon.png" alt="">
                        <h5>
                            Beard Tidy
                        </h5>
                        <div>
                            <p class="info">
                                Tame the tangles and untidy facial hairs like a gentleman with our Beard Tidy services from Avada Barbers.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12 text-center">
                    <button class="button_gold">Read About Our Services</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "SectionService"
}
</script>

<style lang="scss" scoped>
@import "../assets/common.scss";
.container-fluid{
    padding-top: 10rem;
}
.container{
    padding-top: 5rem;
}
p{
    color: $base_color;
    font-weight: bold;
    letter-spacing: .125rem
}
h3{
    color: $secondary_color;
    font-size: 5.125rem;
    font-weight: bold;
}
h5{
    color: $base_color;
    font-weight: bold;
    font-size: 1.875rem;
    margin: 1.875rem 0px;
}
.img_service{
    width: 20%;
}
.img_service_2{
    width: 25%;
}
.info{
    color: gray;
    font-weight: lighter;
}
.col-4{
    padding: 50px;
}
</style>
<template>
    <!-- FIXED -->
    <v-parallax
            height="300"
            src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg"
    >
        <v-layout align-start justify-center column>
            <P>
                Founded by two cook-oholics <i>Andy</i> and <i>Lucy</i>, <strong><i>ARSHI</i></strong>
                is focused at providing the freshest and best quality bakery items rght at your table. We
                came to observe that people after coming to restaurants have to wait for the bakery of the prefered
                item
                to be made fresh and then served. This takes up a lot of time of the customers and being in the 21st
                century,
                time has become most expensive of all.
            </P>
        </v-layout>
    </v-parallax>
<!--    <figure>-->
<!--        <div class="fixed-wrap">-->
<!--            <div id="fixed">-->
<!--                <img src="../../src/assets/cup-cake.jpg" alt="fixed">-->
<!--            </div>-->
<!--            <div class="fixed-text">-->
                <h1>Hello visitors . . .</h1>
                <hr style="background-color: white;">
<!--                <P>-->
<!--                    Founded by two cook-oholics <i>Andy</i> and <i>Lucy</i>, <strong><i>ARSHI</i></strong>-->
<!--                    is focused at providing the freshest and best quality bakery items rght at your table. We-->
<!--                    came to observe that people after coming to restaurants have to wait for the bakery of the prefered-->
<!--                    item-->
<!--                    to be made fresh and then served. This takes up a lot of time of the customers and being in the 21st-->
<!--                    century,-->
<!--                    time has become most expensive of all.-->
<!--                </P>-->

<!--                <P>-->
<!--                    So come to ARSHI, prebooking your order, and enjoy the best ambiance and fulfill your apetite,-->
<!--                    in no wastage of time.-->
<!--                </P>-->
<!--            </div>-->
<!--        </div>-->
<!--    </figure>-->
</template>

<script>
export default {
    name: "fixedBackground"
}
</script>

<style scoped>

/*--- Fixed Background Image --*/

/*figure {*/
/*    position: relative;*/
/*    width: 100%;*/
/*    height: 32%;*/
/*    margin: 0 !important;*/
/*}*/

/*.fixed-wrap {*/
/*    clip: rect(0, auto, auto, 0);*/
/*    position: absolute;*/
/*    top: 0;*/
/*    left: 0;*/
/*    width: 100%;*/
/*    height: 100%;*/
/*}*/

/*#fixed {*/
/*    !* background-image: url('./assets/cup-cake.jpg'); *!*/
/*    background-repeat: no-repeat;*/
/*    background-attachment: fixed;*/
/*    position: fixed;*/
/*    display: block;*/
/*    top: 0;*/
/*    left: 0;*/
/*    width: 100%;*/
/*    height: 100%;*/
/*    background-size: cover;*/
/*    background-position: center center;*/
/*    !* -webkit-transform: translateZ(0);*/
/*    transform: translateZ(0);*/
/*    will-change: transform; *!*/
/*}*/

/*.fixed-text {*/
/*    padding: 10px 20px;*/
/*    font-family: 'Rye', cursive;*/
/*    color: rgba(255, 255, 255, 0.822);*/
/*    background-color: rgba(0, 0, 0, 0.6);*/
/*    font-weight: 500;*/
/*    position: relative;*/
/*    text-align: justify;*/
/*    text-shadow: 1px 1px 10px black;*/
/*}*/

/*.fixed-text p {*/
/*    font-family: 'Amita', cursive;*/
/*    font-size: 30px;*/
/*}*/
</style>
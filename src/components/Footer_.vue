<script setup>
import Footer_SignUp from './Footer_SignUp.vue'

</script>

<template>
    <div class="Footercontainer m-0 p-0 position-relative z-n3">
        <img src="../assets/img/dc-logo-bg.png" alt="" class="position-absolute z-n-3">
        <!-- Da chiedere, perché esce fuori? -->
        <div class="m-auto d-flex containerListe m-auto w-75 h-100 py-5">
            <!-- Da chiedere, come posso mettere che la height si automatica? -->
            <div class="d-flex flex-column">
                <h3>DC COMICS</h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>

                <h3>SHOP</h3>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <div class="d-flex flex-column">
                <h3>DC</h3>
                <ul>
                    <li>Terms of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                </ul>
            </div>

            <div class="d-flex flex-column">
                <h3>Sites</h3>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power</li>
                </ul>
            </div>

        </div>
    </div>
<Footer_SignUp></Footer_SignUp>
</template>

<style scoped>
.Footercontainer {
    /* Da chiedere, perché anche col 100% non prende tutto lo schermo */
    width: 100% !important;
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: 100% 100%;
    /* height: 65vh; */
}

.flex-column *{
    color: white;
}
.containerListe *{
    margin: 0 1rem;
    text-align: left;
}
ul{
    padding: 0;
    margin: 0.5rem 0 !important;
    list-style-type: none;
}
li{
    color: rgb(131, 131, 131) !important;
}
img{
    left: 50%;
    top: 50%;
    transform: translate(0, -50%);
}
</style>
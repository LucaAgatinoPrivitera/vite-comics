<script setup>

</script>

<template>
    <div class="container m-0 p-0">
        <div class="m-auto d-flex containerListe">
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

</template>

<style scoped>
.container {
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: 100% 100%;
    height: 65vh;
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
</style>
<script>
    export default {};
</script>

<template>
    <main>
        <div class="row contents">

            <div class="col-3">
                <div>&rarr;Content goes here&larr;</div>
            </div>

            <div class="col-span"></div>

        </div>


        <div class="row shop">
            <div class="comics">
                <img src="../../vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="">
                <h2>DIGITAL COMICS</h2>
            </div>
            <div class="merchandise">
                <img src="../../vue-dc-comics-1/img/buy-comics-merchandise.png" alt="">
                <h2>DC MERCHANDISE</h2>
            </div>
            <div class="subscription">
                <img src="../../vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="">
                <h2>SUBSCRIPTION</h2>
            </div>
            <div class="location">
                <img src="../../vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="">
                <h2>COMIC SHOP LOCATOR</h2>
            </div>
            <div class="power-visa">
                <img src="../../vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="">
                <h2>DC POWER-VISA</h2>
            </div>
        </div>
    </main>
    

</template>

<style lang="scss" scoped>

    main{
        color: white;
        .contents{
            background-color: black;
            height: 80px;
        }

        .shop{
            background-color: #0282F9;
            display: flex;
            gap: 1rem;
            padding: 15px;
        }

        img{
            width: 70px;
            height: 70px;
        }
    }

</style>
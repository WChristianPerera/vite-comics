<script>
    export default {};

</script>



<template>
    <div class="navigation">

        <div class="small_logo">
            <img src="../../vue-dc-comics-1/img/dc-logo.png" alt="">
        </div>

        <div class="links">
            <ul>
                <li><a href="">CHARACTERS</a></li>
                <li><a href="">COMICS</a></li>
                <li><a href="">MOVIES</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">GAMES</a></li>
                <li><a href="">COLLECTIBLES</a></li>
                <li><a href="">VIDEOS</a></li>
                <li><a href="">FANS</a></li>
                <li><a href="">NEWS</a></li>
                <li><a href="">SHOP</a></li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>

    .navigation{
        display: flex;
        justify-content: space-between;

        ul{
            display: flex;
            gap: 0.5rem;
        }
    
        li{
            list-style: none;
        }
        
        a{
            text-decoration: none;
            color: black;
        }
            

    }





</style>
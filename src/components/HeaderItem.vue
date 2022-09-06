<template>
    <header class="container">
            <img class="dCLogo" src="../vue-dc-comics-1/img/dc-logo.png">
            <ul class="site_navigation_options">
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
    </header>
</template>

<script>
    export default{
        name: 'HeaderItem',
    }
</script>

<style scoped lang="scss">
    header{
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }
    .site_navigation_options{
        display: flex;
        flex-direction: row;
        max-width: 710px;
    }
    .dCLogo{
        width: 80px;
        height: 80px;
    }
    li{
        padding: 50px 15px;
        border: 2px solid transparent;
        &:hover{
            border-bottom: 2px solid #0282f9;
            cursor: pointer;
            color: #0282f9;
        }
    }
</style>
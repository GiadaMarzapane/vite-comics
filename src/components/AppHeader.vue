<script>

export default {
    name: 'AppHeader'
}

</script>

<template>
    <header>
        <img src="../img/dc-logo.png" alt="">
        <nav>
            <ul>
                <li>
                    <a href="#">characters</a>
                </li>
                <li>
                    <a href="#">comics</a>
                </li>
                <li>
                    <a href="#">movies</a>
                </li>
                <li>
                    <a href="#">tv</a>
                </li>
                <li>
                    <a href="#">games</a>
                </li>
                <li>
                    <a href="#">collectibles</a>
                </li>
                <li>
                    <a href="#">videos</a>
                </li>
                <li>
                    <a href="#">fans</a>
                </li>
                <li>
                    <a href="#">news</a>
                </li>
                <li>
                    <a href="#">shop</a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1000px;
        margin: 0 auto;
        height: 60px;
        & img{
            height: 100%;
        }
        nav{
            ul{
                display: flex;
                justify-content: center;
                li{
                    list-style: none;
                    padding: 30px 15px;
                    &:hover{
                        color: #0282f9;
                        border-bottom: 5px solid #0282f9;
                    }
                    a{
                        text-decoration: none;
                        color: inherit;
                        text-transform: uppercase;
                    }
                }
            }
    }
    }
</style>
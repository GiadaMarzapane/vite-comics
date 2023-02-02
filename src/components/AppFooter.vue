<script>

export default {
    name: 'AppFooter'
}

</script>

<template>
    <footer>
        <div class="container">
            <section class="first-section">
                <nav>
                    <ul>
                        <li>
                            <img src="../img/buy-comics-digital-comics.png" alt="digital_comics">
                            <a href="#">digital comics</a>
                        </li>
                        <li>
                            <img src="../img/buy-comics-merchandise.png" alt="dc_merchandise">
                            <a href="#">dc merchandise</a>
                        </li>
                        <li>
                            <img src="../img/buy-comics-subscriptions.png" alt="subscription">
                            <a href="#">subscription</a>
                        </li>
                        <li>
                            <img src="../img/buy-comics-shop-locator.png" alt="comic_shop_locator">
                            <a href="#">comic shop locator</a>
                        </li>
                        <li>
                            <img src="../img/buy-dc-power-visa.svg" alt="dc_power_visa">
                            <a href="#">dc power visa</a>
                        </li>
                    </ul>
                </nav>
            </section>
            <section class="second-section">

            </section>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer{
    height: 100px;
    background-color: #0282f9;
    div{
        max-width: 1000px;
        margin: 0 auto;
        height: 100%;
        section{
            height: 100%;
            display: flex;
            text-align: center;
            justify-content: center;
            nav{
                height: 100%;
                ul{
                    display: flex;
                    text-align: center;
                    justify-content: space-around;
                    height: 100%;
                    li{
                        list-style: none;
                        height: 100%;
                        display: flex;
                        align-items: center;
                        justify-content: space-between;
                        padding: 0 20px;
                        a{
                            text-decoration: none;
                            color: white;
                            text-transform: uppercase;
                            font-size: 0.8rem;
                            padding-left: 10px;
                        }
                        img{
                            height: 40%;
                        }
                    }
                }
            }
        }
    }
}
</style>
<script>

export default {
    name: 'AppHeader',
    data(){
        return{
            headerLinks: [
                {
                    linkName: 'characters',
                    hrefLink: '#'
                }, {
                    linkName: 'comics',
                    hrefLink: '#'
                }, {
                    linkName: 'movies',
                    hrefLink: '#'
                }, {
                    linkName: 'tv',
                    hrefLink: '#'
                }, {
                    linkName: 'games',
                    hrefLink: '#'
                }, {
                    linkName: 'collectibles',
                    hrefLink: '#'
                }, {
                    linkName: 'videos',
                    hrefLink: '#'
                }, {
                    linkName: 'fans',
                    hrefLink: '#'
                }, {
                    linkName: 'news',
                    hrefLink: '#'
                }, {
                    linkName: 'shop',
                    hrefLink: '#'
                }
                
            ]
        }
    }
}

</script>

<template>
    <header>
        <div class="container">
            <img src="../img/dc-logo.png" alt="">
            <nav>
                <ul>
                    <li  v-for="element in headerLinks">
                        <a :href="element.hrefLink">
                            {{ element.linkName }}
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header{
        height: 15vh;
        padding: 10px;
        div{
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 100%;
            img{
                height: 100%;
            }
            nav{
                ul{
                    display: flex;
                    justify-content: center;
                    li{
                        list-style: none;
                        padding: 0px 15px;
                        line-height: calc(15vh - 5px);
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
    }
</style>
<script>

export default {
    name: 'AppMain'
}

</script>

<template>
    <main>
        <section class="jumbotron">
        </section>
        <div class="container">
            <section></section>
        </div>
    </main>
</template>

<style lang="scss" scoped>
    main{
        height: 85vh;
        background-color: #1c1c1c;
        // padding: 30px 0;
        section{
            height: 40%;
            background-image: url('../img/jumbotron.jpg');
            background-size: cover;
            background-repeat: no-repeat;
        }
        div.container{
            max-width: 1000px;
            margin: 0 auto;
            h2{
                color: white;
            }
        }
    }
</style>
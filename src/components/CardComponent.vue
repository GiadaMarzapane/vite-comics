<script>

    export default {
        name: 'cardComponent',
        props:{
            imgSrc: String,
            imgTitle: String
        }
    }

</script>

<template>
    <div class="card">
        <img :src="imgSrc" :alt="imgTitle">
        <h5>{{ imgTitle }}</h5>
    </div>
</template>

<style lang="scss">
div.card{
    width: calc(100% / 6);
    padding: 10px;
    margin-bottom: 25px;
    cursor: pointer;

    img{
        width: 100%;
        height: 140px;
        object-fit: cover;
        object-position: top;
    }
    h5{
        text-transform: uppercase;
        color: white;
    }
}
</style>
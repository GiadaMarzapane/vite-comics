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
        <h4>{{ imgTitle }}</h4>
    </div>
</template>
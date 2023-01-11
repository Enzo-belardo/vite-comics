<script>
export default {
    props: {
        thumb: String,
        price: Number,
        series: String,
        type: String,
    }
}
</script>

<template>
    <div class="product">
        <div>
            <img :src="thumb" :alt="type">
            <p> {{ series ? series.toUpperCase() : "" }} </p>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.product{
    width: calc((100% / 6 ) - 1rem);
    margin: .5rem;
    img{
        width: 100%;
        height: auto;
    }
    p{
        font-size: 1rem;
    }
}

</style>
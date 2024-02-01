<script >

export default {
    name: 'ProductCard',
    props: {
        product: Object, //object passed trough binding in appmain ":product" attribute
        src: String, //string passed trough binding in appmain ":src" attribute
        text: String, //string passed trough binding in appmain ":text" attribute
    }
}

</script>


<template>
    <div class="product card my-4 mx-4">
        <img :src="src" alt="">
        <h6 class="text-primary text-center my-1">{{ text }}</h6>
    </div>
</template>


<style scoped>
.card {
    border-bottom: 1.5px grey;
    border-radius: 40px;


    & img {
        max-height: 150px;
        border: solid 2px rgb(150, 150, 150);
        box-shadow: 1px 2px rgb(0, 0, 0);
        border-top-left-radius: 15px;
        border-bottom-right-radius: 15px;
    }

    & h6 {
        text-transform: capitalize;
        font-style: italic;
        text-shadow: 1px 1px rgb(88, 88, 88);
    }
}

.card:hover {
    filter: drop-shadow(4px 4px 2px rgb(168, 168, 168));
}
</style>
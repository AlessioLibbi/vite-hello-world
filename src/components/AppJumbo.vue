<script>
export default {
    name: "AppJumbo",
    data() {
        return {
            imgText: "Sono il jumbotron"
        }
    }
}
</script>

<template>
    <div class="jumbo-cont">
        <h2 class="jumb-title">{{ imgText }}</h2>
        <img class="img-jumb" src="../assets/vue.svg" alt="">
    </div>
</template>

<style>
.jumbo-cont {
    background-color: blue;
    margin: 0 auto;
}

.jumb-title {
    font-size: 4rem;
    justify-content: center;
    color: white;
    display: flex;
    padding: 20px;
}

.img-jumb {
    width: 100%;
    height: 300px;

}
</style>
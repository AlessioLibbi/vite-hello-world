<script>
export default {
    name: "AppTitle",
    data() {
        return {
            title: "La mia prima app con Vite!"
        }
    }
}
</script>

<template>
    <div class="container">

        <h1 class="main-title">{{ title }}</h1>
    </div>
</template>

<style>
.container {
    width: 90%;
    margin: 0 auto;
}

.main-title {
    color: blue;
    font-size: 5rem;
    display: flex;
    justify-content: center;
    padding: 20px;
}
</style>
<script>
import AppTitle from "./components/AppTitle.vue";
import AppJumbo from "./components/AppJumbo.vue";
export default {
  components: {
    AppTitle,
    AppJumbo,
  },
  data() {
    return {
    }
  }
}
</script>

<template>
  <AppTitle />
  <AppJumbo />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>

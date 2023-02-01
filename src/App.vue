<script>
// import HelloWorld from './components/HelloWorld.vue'
import AppTitle from "./components/AppTitle.vue";
export default {
  components: {
    AppTitle,
  },
  data() {
    return {
      count: 0,
    };
  },
};

</script>

<template>
  <AppTitle />
</template>

<style scoped>

</style>

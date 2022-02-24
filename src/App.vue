<template>
  <div id="app">
    <myHeader />
    <myMain />
    <myFooter />
  </div>
</template>

<script>
import myHeader from "./components/myHeader.vue";
import myMain from "./components/myMain.vue";
import myFooter from "./components/myFooter.vue";

export default {
  name: "App",
  components: {
    myHeader,
    myMain,
    myFooter
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

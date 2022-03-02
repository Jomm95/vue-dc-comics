<template>
  <div id="app">
    <MyHeader />
    <MyContent/>
    <MyMain />
    <MyFooter />
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyMain from "./components/MyMain.vue";
import MyContent from "./components/MyContent.vue";
import MyFooter from "./components/MyFooter.vue";

export default {
  name: "App",
  components: {
    MyHeader,
    MyContent,
    MyMain,
    MyFooter
  },
};
</script>

<style lang="scss">
  @import "./assets/general.scss";

</style>

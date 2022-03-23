<template>
  <div class="containerFooterBottom">
    <h1>My FooterBottom</h1>
  </div>
    
</template>

<script>
export default {
  name: "FooterBottom",
  
};
</script>

<style scoped lang="scss">

@import './src/assets/variables.scss';

.containerFooterBottom {
  height:300px;
  background-image: url('../../assets/img/footer-bg.jpg') left right, url('../../assets/img/dc-logo-bg.png') right no-repeat;
  background-size: 200px, 300px;
  background-repeat: no-repeat;
  
}

</style>
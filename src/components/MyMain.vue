<template>
  <main>
    <div>
      <img src='../assets/img/buy-comics-digital-comics.png'>
      <span>DIGITAL COMICS</span>
    </div>
    <div>
      <img src='../assets/img/buy-comics-merchandise.png'>
      <span>DC MERCHANDISE</span>
    </div>
    <div>
      <img src='../assets/img/buy-comics-subscriptions.png'>
      <span>SUBSCRIPTIONS</span>
    </div>
    <div>
      <img src='../assets/img/buy-comics-shop-locator.png'>
      <span>COMIC SHOP LOCATOR</span>
    </div>
    <div>
      <img class='svg' src='../assets/img/buy-dc-power-visa.svg'>
      <span>DC POWER VISA</span>
    </div>
    
    
  </main>
</template>

<script>
export default {
  name: "MyMain",
  
};
</script>


<style scoped lang="scss">
@import '../assets/variables.scss';

main {
  display:flex;
  height:130px;
  background-color:$primaryColor ;
  justify-content: center;
  align-items: center;
  font-size: 12px;

  div {
    display:flex;
    justify-content: center;
    width:15%;
    

    span {
      line-height: 40px;
      color:white;
      margin-left:5px;
    }
  }
}

img {
  height:40px;
  width:auto;

    // .svg {
    //   height:15%;
    //   width:15%;
      
      
    // }
  
}

.svg {
      height:40px;
      
      
      
      
    }

</style>

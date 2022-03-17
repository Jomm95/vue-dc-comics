<template>
  <div class="containerFooterTop">
    <div class="col-left">
        <h3>DC COMICS</h3>
        <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
        </ul>
        <h3>Shop</h3>
        <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
        </ul>
    </div>

    <div class='col-central'>
        <h3>DC</h3>
        <ul>
            <li>Terms Of Use</li>
            <li>Privacy policy(New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
        </ul>
    </div>

    <div class='col-right'>
        <h3>SITES</h3>
        <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
        </ul>
    </div>
  </div>
    
</template>

<script>
export default {
  name: "FooterTop",
  
};
</script>

<style scoped lang="scss">

@import './src/assets/variables.scss';

.containerFooterTop {
  display: flex;
  height:270px;
  background-image: url('../src/assets/img/footer-bg.jpg');

    .col-left {
        margin-left:180px;
    }

    .col-central {
        margin:0 20px;
    }

    h3{
        color:white;
        font-size: 15px;
        font-weight: 600;
        margin: 18px 0 8px 0;
    }

    ul {
        list-style-type: none;
    
        li {
            font-size: 10px;
            color:$greyText;
        }
    }
}


</style>
<template>
  <div id="app">
    <TheHeader></TheHeader>
    <main class="bg-dark">
      <div class="container mt-5">
        
        
      </div>
      <img class="jumbotron" src="/img/jumbotron.jpg" alt="">
        <product></product>
        <div class="bg-primary pt-5 pb-5 text-white">
          <div class="row">
            <div class="col">
              <img class="img-blue-banner" src="/img/buy-comics-digital-comics.png" alt="">
              <span class="img-title">DIGITAL COMICS</span>
            </div>
            <div class="col">
              <img class="img-blue-banner" src="/img/buy-comics-merchandise.png" alt="">
              <span class="img-title">DC MERCHANDISE</span>
            </div>
            <div class="col">
              <img class="img-blue-banner" src="/img/buy-comics-subscriptions.png" alt="">
              <span class="img-title">SUBSCRIPTION</span>
            </div>
            <div class="col">
              <img class="img-blue-banner" src="/img/buy-comics-shop-locator.png" alt="">
              <span class="img-title">COMIC SHOP LOCATOR</span>
            </div>
            <div class="col">
              <img class="img-blue-banner" src="/img/buy-dc-power-visa.svg" alt="">
              <span class="img-title">DC POWER VISA</span>
            </div>
          </div>
        </div>
    </main>
    <TheFooter></TheFooter>
    <div class="sign-up pt-3 pb-3">
      <button class="text-white ">SIGN-UP NOW!</button>
      <ul class="d-flex">
        <li class="fs-5 fw-bold follow-us">FOLLOW US</li>
        <li>
          <a href="">
            <img src="/img/footer-facebook.png" alt="">
          </a>
        </li>
        <li>
          <a href="">
            <img src="/img/footer-twitter.png" alt="">
          </a>
        </li>
        <li>
          <a href="">
            <img src="/img/footer-youtube.png" alt="">
          </a>
        </li>
        <li>
          <a href="">
            <img src="/img/footer-pinterest.png" alt="">
          </a>
        </li>
        <li>
          <a href="">
            <img src="/img/footer-periscope.png" alt="">
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheFooter from './components/TheFooter.vue'
import product from './components/product.vue'


export default {
  name: 'App',
  components: {
    TheHeader,
    TheFooter,
    product
}
}
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

button {
  border: 2px solid rgb(66, 112, 238);
  background-color: transparent;
  padding: 5px;
}

.follow-us {
  color: rgb(66, 112, 238);
}

.img-blue-banner {
  width: 25px;
}

.img-title {
  font-size: 15px;
  margin-left: 5px;
}

.sign-up {
  background-color: #2F2F2F;
  display: flex;
  justify-content: space-between;
}

.jumbotron {
  height: 600px;
  width: 100%;
}

</style>

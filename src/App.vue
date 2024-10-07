<template>
  <div id="app">
    <img :src="require('@/assets/images/background.jpg')" alt="background">
    <AppHeader /> 
    <main>
      <h2>VUE PROJECT</h2>
      <p id="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora voluptatum vel distinctio, fugit, non temporibus quibusdam neque dolorum dignissimos quas quos similique odio atque expedita earum eligendi eius deleniti dolore.</p>
    </main>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  components: {
    AppHeader, 
    AppFooter  
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}

a{
  text-decoration: none;
  color: inherit;
}

img{
  position: absolute;
  width: 100%;
  height: 100vh;
  z-index: -1;
}

h2, p{
  color: #fff;
}

h2{
  font-size: 80px;
  color: #4CAF50;
  position: absolute;
  top: 45%;
  left: 31%;
  transform: translate(-50%, -50%);
}

#text{
  width: 600px;
  position: absolute;
  top: 57%;
  left: 35%;
  transform: translate(-50%, -50%);
}
</style>

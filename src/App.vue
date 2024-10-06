<template>
  <div id="app">
    <AppHeader /> <!-- 변경된 컴포넌트 이름 -->
    <main>
      <h2>홈페이지 소개</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora voluptatum vel distinctio, fugit, non temporibus quibusdam neque dolorum dignissimos quas quos similique odio atque expedita earum eligendi eius deleniti dolore.</p>
    </main>
    <AppFooter /> <!-- 변경된 컴포넌트 이름 -->
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'; // 변경된 컴포넌트 이름
import AppFooter from './components/AppFooter.vue'; // 변경된 컴포넌트 이름

export default {
  components: {
    AppHeader, // 변경된 컴포넌트 이름
    AppFooter  // 변경된 컴포넌트 이름
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}

main {
  padding: 2em;
}
</style>

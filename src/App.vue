<template>
  <HeaderTop/>
  <img id="sunset" alt="Vue logo" src="./assets/sunset.jpg">
  <HelloWorld msg="Hellloooooo world!"/>
  <FooterTop/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeaderTop from './components/HeaderTop.vue'
import FooterTop from './components/FooterTop.vue'

export default {
  name: 'App',
  components: {
    HeaderTop,
    HelloWorld,
    FooterTop
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin-left: -8px;
}
#sunset{

  width:100vw;
}
</style>

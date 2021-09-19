<template>
  <header-bar></header-bar>
  <side-bar></side-bar>
  <content></content>
  <footer-bar></footer-bar>
  <!-- <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/> -->
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import HeaderBar from './components/HeaderBar.vue';
  import SideBar from './components/SideBar.vue';
  import Content from './components/Content.vue';
  import FooterBar from './components/Footer.vue';
  export default defineComponent({
    name: 'App',
    components: {
      HeaderBar,
      SideBar,
      Content,
      FooterBar,
    }
  })
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>

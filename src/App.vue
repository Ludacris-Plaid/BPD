<template>
    <div>
      <Header></Header>
      <Ticker></Ticker>
      <Body></Body>
    </div>
</template>

<script>

import Header from "@/components/Header.vue";
import Ticker from "@/components/Ticker.vue";
import Body from "@/components/Body.vue";


export default {
  name: 'App',
  components: {
    Header, Ticker, Body,
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
}
</style>

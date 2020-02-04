<template>
  <div id="app">
    <appHeader/>
    <router-view />
  </div>
</template>


<script>

import appHeader from "@/components/AppHeader.vue"

export default {
  components:{
    appHeader
  }
}
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>

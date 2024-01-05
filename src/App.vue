<template>
  <div id="app">
    <router-view></router-view>
    <header-comp />
  </div>
  
</template>

<script>
import headerComp from '@/components/headerComp.vue';

export default {
  name: 'App',
  components: {
    headerComp
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
  margin-top: 30px;
}

*,
*::before,
*::after {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}


a {
    text-decoration: none;
    color: #000;
}

button,
input {
    outline: none;
    border: 0;
    background: transparent;
}

ul,
li {
    list-style: none;
}

.container {
    max-width: 1344px;
    margin: 0 auto;
    padding: 0px 10px;
}


</style>

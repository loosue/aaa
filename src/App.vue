<template>
  <div id="app">
    <my-header></my-header>
    <hello></hello>
    <my-footer></my-footer>
  </div>
</template>

<script>
import Hello from './components/Hello'
import myHeader from './components/Header'
import myFooter from './components/Footer'

export default {
  name: 'app',
  components: {
    Hello,myHeader,myFooter
  }
}
</script>

<style>
html,body,header,footer,h1,h2,p,ul,li,div{padding: 0;margin: 0;}
h1, h2 {font-weight: normal;}
ul {list-style-type: none;}
li {display: inline-block;margin: 0 10px;}
a {color: #42b983;}

#app {font-family: 'Avenir', Helvetica, Arial, sans-serif;-webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;color: #2c3e50;}
</style>

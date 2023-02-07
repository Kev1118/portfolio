<template>
  <div id="app">
    <navbarComponent></navbarComponent>
  </div>
</template>

<script>
import navbarComponent from './components/layout/navbar-component.vue';
export default {
  name: 'App',
  components:{
    navbarComponent
  }

}
</script>

<style>
.body{
  background-color: #f6f5f5;
  margin: 0px;
  padding: 0px;
}
.ul{
  list-style-type: none;
}
a{
  text-decoration: none;
}
section{
  width: 100%;
  height: 94vh;
  position: relative;
}
</style>

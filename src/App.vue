<template>
  <Header />
  <Home />
  
</template>

<script>
import Header from './components/Header.vue';
import Home from './components/Home.vue';


export default {
  name: 'App',
  components: {
    Header,
    Home,
    
  }
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
}

</style>

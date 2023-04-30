<template>
  <div class="content">
    <Header />
    <Home />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Home from "./components/Home.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Home,
    Footer,
  },
};
</script>

<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
  padding: 0;
}

.content {
  min-width: 768px;
  max-width: 1440px;
  margin: 0 auto;
}
</style>

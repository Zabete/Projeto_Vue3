<!-- A vue é impressa no componente <router-view/> daí se repetirem -->

<template>
  <div>
    <Navbar :logo="logo_src" :alt="app_name" />
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
    Footer
  },
  data() {
    return {
      logo_src: "/img.logo.png",
      app_name: "burger"
    }
  }
}
</script>

<style>

</style>
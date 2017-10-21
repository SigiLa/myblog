<template>
  <div id="app">
    <!--header-->
    <div class="head">
      <blog-nav></blog-nav>
    </div>
    <!-- end header -->


    <div class="bg-gray-dark">
      <router-view></router-view>
    </div>


    <blog-footer></blog-footer>

  </div>
</template>

<script>
  import Nav from './components/Nav.vue'
  import Footer from './components/Footer.vue'

  export default {
    name: 'app',
    components: {
      'BlogNav': Nav,
      'BlogFooter': Footer
    }
  }

</script>

<style>
#app{
  display: flex;
  flex-direction: column;
}

</style>

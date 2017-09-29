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


    
  </div>
</template>

<script>
  import Nav from './components/Nav.vue'
  require('./assets/imgs/alien.png')
  require('./assets/imgs/postmordennism.jpg')

  export default {
    name: 'app',
    components: {
      'BlogNav': Nav,
    }
  }

</script>

<style>
  div.head {
    display: flex;
    justify-content: center;
  }

.bg-gray-dark{
  background-color: #24292e;
}

</style>

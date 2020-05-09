<template>
  <div id="app">
    <!-- <topNav></topNav> -->
    <router-view/>
    <router-link to="/register">注册</router-link>
  </div>
</template>

<script>
import topNav from '@/components/common/topNav'
export default {
  name: 'App',
  components:{
    topNav
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

</style>

<template>
  
  <div class="app">
    <navbar style="margin-top: -20px;margin-right: -20px;margin-left: -20px;"/>
    <router-view />
  </div>  
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  components: { Navbar },
  
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.app {
  padding: 20px;
}
</style>

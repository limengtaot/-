<template>
  <div class="Home" id="Home">
      <Home-header></Home-header>
      <Home-cat></Home-cat>
  </div>
</template>

<script>

import HomeHeader from './components/HomeHeader'
import HomeCat from './components/HomeCat'

export default {
  name: 'Home',
  components:{HomeHeader,HomeCat}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped  lang="scss">
.Home{
  visibility: visible;
}
</style>

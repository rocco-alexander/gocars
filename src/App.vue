<template>
  <nav-bar/>
<div class="content">
  <router-view/>
</div>
</template>

<script>
import NavBar from './components/NavBar.vue';
export default {
  components:{NavBar}
}
</script>

<style lang="scss">
  *{
    margin:0; 
    padding: 0;
  }
  .content{
  
  }
</style>

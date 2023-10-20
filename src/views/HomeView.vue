<template>
  <div class="home">
    <content-container/>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import ContentContainer from '@/components/ContentContainer.vue';
export default {
  name: 'Home',
  components:{NavBar,ContentContainer}
}
</script>
<style lang="scss" scoped>
  *{
    padding:0;
    margin:0;
  }
  body{
    background: #F6FAFF;
  }
  .home{
    margin-left: 150px; // VERY IMPORTANT - SPACES THE HORIZONTAL NAVIGATION BAR
    display: flex;
    justify-content: center;
  }
</style>
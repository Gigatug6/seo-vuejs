<template>
<infinite-slide-bar :barStyle="{ background: '#42b883', height:'300px', width:'100%' }">
  <div class="slide-bar">
    <img src="../assets/images/slideBar/walter.webp" width="100%" height="100%"/>
  </div>
</infinite-slide-bar>
</template>

<script>

  import InfiniteSlideBar from 'vue-infinite-slide-bar'

  export default {
    name: 'InfiniteBar',
    components: {
      InfiniteSlideBar
    },
  };
</script>

<style lang="scss">
  .slide-bar {
    width: 100%;
    height: 100%;
  }
</style>
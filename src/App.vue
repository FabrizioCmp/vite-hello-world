
<script>
import AppTitle from './components/AppTitle.vue';

export default {

  components: { AppTitle },
  data() {
    return {

    }
  }
}

</script>

<template>
  <div class="title">
    <AppTitle></AppTitle>
    <div class="img_box">
      <img src="../src/assets/vite.svg" alt="">
    </div> 
  </div>
</template>

<style>
  .title{
    text-align: center;
    margin: 2rem 0;
  }
</style>
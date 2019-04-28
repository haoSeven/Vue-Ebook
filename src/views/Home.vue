<template>
  <div class="home">
   <span class="icon-book"></span>
    <span class="icon-cart"></span>
  </div>
</template>

<script>
  import Epub from 'epubjs'
  global.ePub = Epub
export default {
}
</script>

<style scoped>
  .icon-book{
    font-size: 30px;
    color: red;
  }
</style>

<template>
  <div>
    <Menu :scrolling="scrolling"></Menu>
    <nuxt />
    <Footer />
  </div>
</template>
<script>

  function scroll() {
    this.scrolling = (window.scrollY > 0);
  }

  export default {
    data() {
      return {
        scrolling: false
      };
    },
    mounted() {
      window.addEventListener('scroll', scroll.bind(this));
    }
  };

</script>
<style lang="less">
  body {
    overflow-y: scroll;
  }
</style>

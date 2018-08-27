<template>
  <section>
    <Intro />

  </section>
</template>

<script>
import Logo2 from "~/components/Logo2.vue";

export default {
  components: {
    Logo2
  }
};
</script>

<style>
@font-face {
  font-family: 'ProximaSoftMark';
  src: url('~/assets/fonts/proxima-soft-medium-mark.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
}
body {
  font-family: 'ProximaSoftMark';
  font-size: 1rem;
}
#menu {
  //opacity: 0;
}
</style>

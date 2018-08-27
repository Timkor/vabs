<template>
    <b-container>
      <h1></h1>
    </b-container>
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

.container2 {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  /*font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links {
  padding-top: 15px;
}
</style>

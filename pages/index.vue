<template>
  <div class="index-page">
    <Intro />

    <section>
        <b-container>
          <h1>
            Assistance adapted to <b>you</b>
          </h1>
        </b-container>
    </section>
  </div>
</template>

<script>
import Logo2 from "~/components/Logo2.vue";

export default {
  components: {
    Logo2
  }
};
</script>
<style lang="less">
  .index-page {
    section {
      padding: 10rem 0;
      height: 1vh;
    }
  }
</style>

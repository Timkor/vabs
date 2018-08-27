<template>
  <div id="footer">
    <logo/>
    <h2 class="subtitle">
      Virtual Assistant Business Services
    </h2>
    <div class="links">
      <a href="#">About</a>
      <a href="#">Blog</a>
      <a href="#">Contact</a>
      <a href="#">Privacy Policy</a>
      <a href="#">Terms of Agreement</a>
    </div>
  </div>
</template>
<style lang="less">
  #footer {

    min-height: 50vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;

    .title {
      /*font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; */
      display: block;
      font-weight: 300;
      font-size: 100px;
      color: #35495e;
      letter-spacing: 1px;
    }
    .subtitle {
      padding-top: 15px;
      font-weight: 300;
      font-size: 42px;
      color: #526488;
      word-spacing: 5px;
    }
    .links {
      a {
        margin: 0 .5rem;
      }
    }
  }
</style>

<template>
  <div class="home">
    <div class="d-flex justify-content-center">
      <bot-list />
    </div>
    <hr />
    <!-- <img alt="Uptrading logo" src="../assets/uptrading-logo.png" width="450px" class="my-5" /> -->
    <div title="Uptrading logo" class="logo-svg my-5 mx-auto" />
    <div>
      <h1>Welcome to the Uptrading UI</h1>
    </div>
    <div>This page allows you to control your trading bot.</div>
    <br />
    <p>
      If you need any help, please refer to the
      <a href="https://www.egiftcard.cc/en/latest/">Uptrading Documentation</a>.
    </p>

    <p>Have fun - <i>wishes you the Uptrading team</i></p>
  </div>
</template>

<script setup lang="ts">
import BotList from '@/components/BotList.vue';
</script>

<style lang="scss" scoped>
.home {
  margin-top: 1.5em;
}
.logo-svg {
  -webkit-mask: url(../assets/uptrading-logo-mask.png) no-repeat center;
  -webkit-mask-size: 240px 240px;
  mask: url(../assets/uptrading-logo-mask.png) no-repeat center;
  mask-size: contain;
  width: 250px;
  height: 250px;
}
</style>

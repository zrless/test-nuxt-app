<template>
  <div>
    <h1 class="about">my页面</h1>
    <nuxt-link to="/">/toIndex</nuxt-link>
    <nuxt-link to="/about">/about</nuxt-link>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({});
</script>

<style lang="scss" scoped>
.about {
  color: red;
}
</style>

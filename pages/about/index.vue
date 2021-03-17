<template>
  <div>
    <h1 class="about">about页面</h1>
    <nuxt-link to="/">/toIndex</nuxt-link>
    <nuxt-link to="/my">/my</nuxt-link>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({});
</script>

<style scoped>
.about {
  color: red;
}
</style>

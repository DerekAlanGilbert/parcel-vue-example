<template lang="html">
  <div>
    Hello {{ bundler }}
  </div>
</template>

<script lang="js">
import Vue from "vue";
export default {
  data() {
    return {
      bundler: "Parcel"
    };
  }
}
</script>

<style lang="scss" scoped>
.container {
  color: green;
}
</style>
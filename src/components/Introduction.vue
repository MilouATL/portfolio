<template>
  <div class="introduction">
    <h1>{{ name }}</h1>
    <h2>{{ jobFunction }}</h2>
  </div>
</template>

<script>
export default {
  name: "Introduction",
  props: {
    name: String,
    jobFunction: String,
    test: Number
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

<template>
  <h1>La mia prima app con Vue CLI! {{msg}}</h1>
</template>

<script>
export default {
  name: 'Title',
  props: {
      msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>

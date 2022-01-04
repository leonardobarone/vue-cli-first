<template>
  <div class="container">
      <img src="../assets/dumbo.jpg" default :alt="text">
  </div>
</template>

<script>
    export default {
    name: 'Hero',
    props: {
        text: String
    }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    * {
        margin: 0rem;
        padding: 0rem;
        box-sizing: border-box;
    }
</style>
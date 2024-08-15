<!--
Add "scoped" attribute to limit CSS to this component only <style scoped>
-->

<template>
  <div class="hello">
    <h3>{{ msg }}</h3>
  </div>
</template>

<style scoped>
  .hello {
    margin: 40px 0 0;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>

<script>
export default {
  name: 'MessageComponent',
  props: {
    msg: String
  }
}
</script>

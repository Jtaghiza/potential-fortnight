<template>
  <div id="app">
    <div v-cloak>
      {{msg}}
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App' + new Date().toLocaleString()
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
$primary-color: red;
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;

    li {
      color: $primary-color;
    display: inline-block;
    margin: 0 10px;
  }
}
[v-cloak] {
  display: none;
}

a {
  color: #42b983;
}
</style>

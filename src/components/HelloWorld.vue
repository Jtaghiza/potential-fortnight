<template>
  <div id="app">
  <span v-bind:title="msg">
    Hover your mouse over me for a few seconds
    to see my dynamically bound title!
  </span>
  <span v-bind:title="msg"></span>


  <ul>
    <li>
      hi
    </li>
    <li>
      hi2/
    </li>
    <li>
      hi3
    </li>
</ul>
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



a {
  color: #42b983;
}
</style>

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>wogde</p>
    <table><tr><td>

    </td></tr></table>
  </div>
</template>

<script>
  list-style-type: none;
  padding: 0;
export default {
name: 'HelloWorld',
props: {
    msg: String
}
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 h3 {
     margin: 40px 0 0;
 }
ul {
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

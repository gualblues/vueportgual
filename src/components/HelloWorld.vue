<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Desenvolvedor fullstack | Músico | Iustrador <br>
      check out the
      <a href="mailto:gualbluessound@gmail.com" target="_blank" rel="noopener">mailto:gualbluessound@gmail.com</a>.
    </p>
    
  </div>                           
</template>

<script>
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
body{
  margin:0;
  padding:0;
  background-color: #2c3c4b !important;
}
</style>

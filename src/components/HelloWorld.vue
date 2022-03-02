<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      This application is for demonstration purposes. The goal of this project is to
      showcase a multi-step form application. The experience should allow the user
      to have a easy way to navigate the form.
    </p>
    <h3>Let's begin!</h3>
    <br>
    <button type="button">Start Form</button>
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
</style>

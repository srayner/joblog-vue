<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      An example application to demonstrate how Vue.js can be used for a
      frontend user interface <br />
      for communicating with a backend API. For details on the backend API look
      here
      <a
        href="https://github.com/srayner/joblog-backend"
        target="_blank"
        rel="noopener"
        >Backend API</a
      >.
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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

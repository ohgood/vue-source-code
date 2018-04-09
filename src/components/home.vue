<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <a
          href="http://www.coding.ink/blog"
          target="_blank"
        >
          博客
        </a>
      </li>
      <li>
        <a
          href="http://116.196.80.176/#/"
          target="_blank"
        >
          VUE小案例
        </a>
      </li>
      <li>
        <a
          href="https://github.com/ohgood"
          target="_blank"
        >
          github
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to my website'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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

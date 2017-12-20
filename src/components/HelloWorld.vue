<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    
    <router-view></router-view>
    <h2>Essential Links</h2>
    <ul>
      <li><router-link to= "/"> Home</router-link></li>
      <li><router-link to= "/journal"> journal</router-link></li>
     <li><router-link to= "/calendar"> Calendar</router-link></li>
      
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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

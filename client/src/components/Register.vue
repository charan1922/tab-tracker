<template>
  <div>
<h1>Register</h1>
 <input type="email" name="email" placeholder="email">
<br>
<input type="password" name="password" placeholder="password">
<br>
<button type="button">Register</button>

  </div>
</template>

<script>
export default {
  data () {
    return {
      email:'abc',
      password:'abc'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

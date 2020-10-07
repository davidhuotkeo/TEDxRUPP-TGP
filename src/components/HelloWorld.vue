<template>
  <div class="hello">
    <p1>{{ msg }}</p1><br><br><br><br>
    <input type="button" value="Main website" id="button">
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
#button{
    background-color: red;
  border: none;
  color: white;
  padding: 5px 40px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 12px;
}
</style>

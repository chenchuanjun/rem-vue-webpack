<template>
  <div class="hello">
    <div id="test">无可奈何花落去，似曾相识燕归来</div>
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
#test {
    color: red;
    width: 750px;
    height: 200px;
    font-size: 24px;
    opacity: 0.8;
    margin-bottom: 120px;
  }
</style>

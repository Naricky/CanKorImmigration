<template>
  <div>
    <img class='flag' src='../assets/flag.png'></img>
    <div class='title'> Welcome to CanCor Immigration</div>
  </div>
</template>

<script>
export default {
  name: 'topHeader',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.title {

  text-align: center;
  display:inline-block;
}

.flag {
  height: 80%;
  margin: 5px auto;
  display:inline-block;
}

</style>

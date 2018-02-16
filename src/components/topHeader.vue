
<template>
  <div>
    <div class='headerAssets'>
      <img class='flag' src='../assets/flag.jpg'></img>
      <div class='title'> Welcome to CanCor Immigration</div>
    </div>

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

.headerAssets {
  width: auto;
}

.title {
  text-align: center;
  font-size: 45px;
  color: blue;
  margin-bottom: -25px;
  width: auto;
  display:block;
}

.flag {
  height: 85px;
  margin: 5px auto;
  padding: 15px;
  display:block;
}

</style>

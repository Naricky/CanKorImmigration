<template>
  <div id="app">
    <topHeader class='topHeader'></topHeader>
    <br/>
    <introduction class='introduction'></introduction>
    <br/>
    <bottomFooter class='bottomFooter'></bottomFooter>
  </div>
</template>

<script>

import topHeader from './components/topHeader'
import introduction from './components/introduction'
import bottomFooter from './components/bottomFooter'

export default {
  name: 'App',
  components: {
    topHeader, introduction, bottomFooter
  }
}
</script>

<style>

body{
 font: 30px sans-serif;
}

.topHeader , .bottomFooter {
  height: 250px;
  background-color:blue;
}

.introduction {
  height: 850px;
  width: 1200px;
  margin: 50px 50px;
}



.title{
  font-size: 15px;
}



</style>

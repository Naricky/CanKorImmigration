<template>
  <div id="app">
    <topHeader class='topHeader'></topHeader>

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
 color: #119da3;
}

.topHeader , .bottomFooter {
  height: 200px;
  background-color: #F6F6F6;
}

.introduction {
  height: 850px;
  width: 1200px;
}

</style>

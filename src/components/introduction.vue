<template>
  <div>
    <ul class='navbar'>
      <li><div @click='showEmployerSection'>EMPLOYER</div></li>
      <li><div @click='showEmployeeSection'>EMPLOYEE</div></li>
    </ul>
    <div class='EmployerSearch'>
      <!-- Employer Search bar requires: type of job // experience // type of working status-->
    </div>
    <div class='EmployeeSearch'>
      <!-- Employee Search bar requires : desire Country // occupational type // objective of this job search-->
    </div>
  </div>
</template>

<script>
export default {
  name: 'Introduction',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    showEmployerSection: function() {
      alert('Hellow Employer'); // On Click, slide down to the Employer form along with making the form visible
    },
    showEmployeeSection: function() {
      alert('Hellow Employee'); // On Click, slide down to the Employer form along with making the form visible
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.navbar{
    width: 1200px;
}
ul{
  text-align: center;
}
ul li{
display: inline-block;
padding: 20px 36px;
}
.last{
  border-radius: 0px 120px 120px 0 ;

}
.first{
  border-radius: 120px 0px 0px 120px ;
}
li:hover{
  background: #66b2ab;
  box-shadow: inset 0px 0px 2px 2px #327670;
    color: #FFF;
}
a{
  text-decoration: none;
    font-size: 15px ;
    color: #119da3;
    font-family: sans-serif;
    font-weight: bold;
}
a:hover{
   color: #FFF;
}


</style>

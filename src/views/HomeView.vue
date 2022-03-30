<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png" />

    <Contador/>
    <Cuadrado/>
    <Botones/>


  </div>
    



</template>

<script>
import Contador from '../components/Contador.vue'
import Cuadrado from '../components/Cuadrado.vue'
import Botones from '../components/Botones.vue'
// @ is an alias to /src

export default {
  components: {
     Contador, 
     Cuadrado,
     Botones,
      },
	name:'HomeView',
  }
</script>


<style>

div{
  margin-bottom: 10px;
}
   
  button{
    font-size: 40px;
    font-weight: bold;
    color: #42b983;
    margin: 0px 10px;
   }

 .contador{
  font-size: 50px;
  font-weight: bold;
  color: #42b983;
 }

.cuadrado{
  font-size: 20px;
  font-weight: bold;
  color: #42b983;
}


</style>
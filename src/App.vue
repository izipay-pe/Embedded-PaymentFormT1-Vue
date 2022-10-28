<template>
  <div id="app">
    <h2>Ejemplo de un formulario Incrustado con Vue.js</h2>
    
    <div>
      <img alt="Vue logo" src="./assets/Logo-161x66.png" />
    </div>  

    <img alt="Vue logo" src="./assets/logo.png"/> 
    
    <hr>
    <AddForm/>  
    <hr>
  </div>
</template>

<script>
import AddForm from './components/AddForm.vue'

export default {
  name: 'app',
  components: {
    AddForm
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img{
  max-width: 100px;
  max-height: 161px;
}

/*Estilos para el formulario*/
.formulario{    
    background-color: #FFF;
    border-radius: 5px;
    box-shadow: 0 10px 25px rgba(92, 99, 105, .2);
    padding: 20px;  
    margin-bottom: 20px;  
}

.kr-embedded .kr-payment-button {
    color: #ffffff !important;
    background-color: #00A09D !important;
}

.kr-embedded .kr-payment-button:hover {
    color: #ffffff !important;
    background-color: #3DD2CE !important;
}

hr{   
    border-block-end: #b3b6b5;
    width:          400px; 
}

</style>

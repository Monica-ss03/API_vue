<template>
    <div class="pelicula">
    <div class="row">
    <div class="col-8 col-sm-8">
         <img  class="img-fluid shadow" :src="imgsrc"/>
    </div>
    <div class="col-4 col-sm-4">
    <h3 class="titulo text-light">elefante</h3>
    </div>
    </div>
    </div>
</template>

<script>
export default {
  name: 'componente-pelicula',
  props: {
    infopelicula: Object
  },
  data(){
    return {
      imgsrc: "https://img.remediosdigitales.com/4dbe44/todo-lo-que-necesitas-llevar-para-un-safari-por-africa/450_1000.jpg"
    }
  },
  mounted (){
    
  },
  methods:{
      
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

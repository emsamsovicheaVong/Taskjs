<template>
  <div id="app">
    <ol>
      <li v-for="vichea in services">
        {{vichea.id}}
        {{vichea.subject}}
      </li>
    </ol>
  </div>
</template>

<script>



export default {
  name: 'App',
  components: {
  
  },
     
    data(){
    return{
       services:[
      {
       id:1,
       subject:"Burger",
       active:true
      },
      {
        id:2,
       subject:"Pizza",
       active:true
      },
      {
        id:3,
       subject:"Coke",
       active:true
      }
      ]

    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

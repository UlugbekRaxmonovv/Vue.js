

<template>
   <div class="container p-4">
     
      <h1>counter:{{counter}} </h1>
      <div class="d-flex">
        <button v-on:click='go' class="btn btn-success ">Add</button>
        <button v-on:click='btn' class="btn btn-danger">delete</button>
      </div>
    </div>
  
</template>

<script>
   export default{
    data(){
      return{
        counter:0
      }
    },
    methods:{
      go(){
        this.counter += 1
      },
      btn(){
        this.counter -=1
      },
    },
    
   }
</script>

<style>

</style>

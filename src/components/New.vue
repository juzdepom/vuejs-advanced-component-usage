<template>
  <div>
    <h3>New Quote</h3>
    <button @click="increase">Increase Counter</button>
    <p>
      {{counter}}
    </p>
  </div>


</template>

<script>
  export default {
    data: function(){
      return {
        counter: 0,
      }
    },
    methods: {
      increase(){
        this.counter++
      }
    }
    deactivated(){

    },
    activated(){
      
    }
  }
</script>

<style scoped>

</style>

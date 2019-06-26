<template>
  <div>
   <div>{{massage}}</div>
  <button v-on:click="getMes()">奥术大师</button>
  </div>

 

</template>

<script>
  export default {
    data (){
      return{
        massage:'首页'
      }
    },
    methods:{

      getMes () {
        console.log(this.massage)
      }

    }

  }
</script>

<style scoped>

</style>

<template>
  <div>
     <p>歡迎來到{{msg}}的專案</p>
     <button @click="getin">進入todolist</button>
     
  </div> 
</template>
// import demo from '路徑'
<script>
export default {
  name: 'HelloVue',
  data () {
    return {
      msg: '周培瑜',
      getin(){
        window.open('')
      }
    }  
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

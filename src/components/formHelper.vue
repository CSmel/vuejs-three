<template>
  <div>
<h1>Please fill out my form....</h1>
  <form>
    <div id="form-header"></div>
    <slot name="form-header"></slot>
    <div id="form-fields">
      <slot name="form-fields"></slot>

    </div>
    <div id="form-controls">
      <slot name="form-controls"></slot>

    </div>
    <div id="useful-links"></div>
    <ul>
      <li> <a href="#">Link 1</a></li>
      <li> <a href="#">Link 2</a></li>
      <li> <a href="#">Link 3</a></li>
      <li> <a href="#">Link 4</a></li>


    </ul>
  </form></div>
</template>
<script>
  export default {
    components:{

    },
    data(){
      return{

      }
    },
    methods:{

    }
  }
</script>
<style scoped>
  h1{
    color: green
  }
</style>
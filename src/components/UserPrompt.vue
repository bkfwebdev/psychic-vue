<template>
   <p id="userprompt">{{message}}</p>
</template>

<script>
export default  {
  name:'Instructions', 
  props:{
      message:String,
  }     
}
</script>
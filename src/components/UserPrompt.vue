<template>
   <p class="userprompt">{{message}}</p>
</template>

<script>
export default  {
  name:'Instructions', 
  props:{
      message:String,
  }     
}
</script>
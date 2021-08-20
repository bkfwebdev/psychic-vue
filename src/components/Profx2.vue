<template>
          <img v-bind:src="require('../assets/' + img)" />
</template>

<script>
export default {
  data: function() {
    return {
      img: "profx.jpg"
    };
  }
};
</script>
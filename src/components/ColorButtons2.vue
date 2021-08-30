<template>
  <div :v-for="color in colors" :key="color.id">
    <ColorButton :color="color"></ColorButton>
  </div>
</template>

<script>
import ColorButton from "./ColorButton";
export default {
  name: "ColorButtons2",

  components: {
    ColorButton,
  },

  props: {
    colors: Array,
  },
};
</script>

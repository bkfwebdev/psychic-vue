<template>
  <button @click="handleClick" :class="color">{{ color }}</button>
</template>

<script>
export default {
  name: "ColorButton",
  props: {
    color: String,
  },
  methods: {
    handelClick() {
      alert(`You clicked the ${this.color} button`);
    },
  },
};
</script>

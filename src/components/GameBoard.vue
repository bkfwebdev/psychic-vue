<template>
  <div class="container">
    <Header />
    <Profx />
    <ColorButtons2 :colors = "colors" />
    <Instructions />
    <UserPrompt />
  </div>
</template>

<script>
import Header from "./Header";
import Profx from "./Profx2";
import ColorButtons2 from "./ColorButtons2";
import Instructions from "./Instructions";
import UserPrompt from "./UserPrompt";

export default {
  name: "GameBoard",

  components: {
    Header,
    Profx,
    ColorButtons2,
    Instructions,
    UserPrompt,
  },

  props: {
    colors: Array
  },
};
</script>

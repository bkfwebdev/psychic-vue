<template>
  <GameBoard :colors = "colors"></GameBoard>
</template>

<script>
import GameBoard from "./components/GameBoard.vue";

export default {
  name: "App",
  components: {
    GameBoard,
  },

  data() {
    return {
      snarkyComments: [
        "!!!... ",
        " WOW!, your psychic abilities are amazing!.",
        " You can do better,maybe after a cup of coffee.",
        " Okay maybe you are not psychic...today",
        " Perhaps you were distracted...",
        " Pick this one first next time, trust your instincts.",
        " It was only a matter of time...right?",
        " Sorry kid, you aint got it...",
        " Dude! WTF, you only had 7 choices!",
        " You need to find a short bridge & take a long walk",
      ],
      colors: ["red", "orange", "yellow", "green", "blue", "indigo", "violet"],
      numOfGuesses: 0,
      computerChoice: null,
      userChoice: null,
    };
  },
};
</script>

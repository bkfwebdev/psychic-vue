<template>
<div class = "container">
<Header/>
<Profx/>
<ColorButtons/>
<Instructions/>
<UserPrompt/>
</div>
</template>

<script>
import Header from './Header';
import Profx from './Profx';
import ColorButtons from './ColorButtons'
import Instructions from './Instructions';
import UserPrompt from './UserPrompt';


export default {
  name: 'GameBoard ',
  components: {
    Header,
    Profx,
    ColorButtons,
    Instructions,
    UserPrompt   
  }
}
</script>

<style>

</style>
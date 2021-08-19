<template>
<Header/>
<Profx/>
<ColorButtons/>
<Instructions/>
<UserPrompt/>
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
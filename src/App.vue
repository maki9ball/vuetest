<template>
<div>
  <diceHeader/>
  <diceMain/>
  <diceFooter/>
</div>
</template>

<script>
import diceHeader from './components/DiceHeader';
import diceMain from './components/DiceMain';
import diceFooter from './components/DiceFooter';

export default {
  components: { diceHeader, diceMain, diceFooter }
}
</script>

<style>
</style>

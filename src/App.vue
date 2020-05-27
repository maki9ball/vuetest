<template>
<div>
  <diceHeader/>
  1の目
  <diceMain/>
  <h2>2の目</h2>
  <diceMain/>
  <h2>3の目</h2>
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

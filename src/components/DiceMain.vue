<template>
<div>
    <h2>{{valueOfDice}}</h2>
    <button class="myBody" @click="rollDice">roll</button>
</div>
</template>

<script>
var min = 1 ;
var max = 6 ;

var valueOfDice = "-";
export default {
    data(){
        return{
            valueOfDice: valueOfDice
        };
    },
    methods:{
        rollDice(){
            this.valueOfDice = Math.floor( Math.random() * (max + 1 - min) ) + min ;
        }
    }
}
</script>

<style scoped>
</style>

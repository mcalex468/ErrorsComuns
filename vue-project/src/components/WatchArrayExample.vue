<script setup>
import { ref, watch } from 'vue'
const numbers = ref([])

watch(numbers, () => console.log('new number added'))

watch(numbers.value,(newValue,oldValue) => console.log(newValue,oldValue))

watch(numbers,() => console.log(numbers),{deep:true}) 

const randomNum = () => numbers.value.push(Math.random())
</script>

<template>
  <button @click="randomNum">Add Random Number</button>
</template>

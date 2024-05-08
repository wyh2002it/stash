<template>
  <h1>{{ count }}</h1>
  <button @click="count++">++</button>
</template>

<script>
export default {
  name: app
}
</script>

<script setup>
  import {ref} from 'vue'
  let count = ref(0)
  
</script>
<style>

</style>

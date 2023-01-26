<script setup>
import LikeSad from "./components/LikeSad.vue"
</script>

<template>
  
  <div v-for="n in 10" :key="n">{{  }} <LikeSad></LikeSad></div>

</template>

<style scope></style>
<template>
  <div class="bg-dark">
    <p>Page id is {{ id }}</p>
  </div>

  <div class="flex flex-row">
    <div class="basis-1/4">01</div>
    <div class="basis-1/4">02</div>
    <div class="basis-1/2">03</div>
  </div>
  <Contact></Contact>
  <ContactDetail/>
</template>

<script setup>
const { id } = useRoute().params
useState('id',() => id)
</script>

<style scoped>


</style>
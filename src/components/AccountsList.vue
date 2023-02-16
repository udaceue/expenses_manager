<template>
  <div class="accounts-container">
    <div class="grid-item">1</div>
    <div class="grid-item">1</div>
    <div class="grid-item">1</div>
    <div class="grid-item">1</div>
    <div class="grid-item">1</div>
    <div class="grid-item">1</div>
  </div>
</template>

<script>
export default {
  name: "AccountsList"
}
</script>

<style scoped>
.accounts-container{
  display:grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 0.6rem;
}
.grid-item{
  height: 8rem;
  background: darkslategrey;
  border-radius: 2rem;
}
</style>
<script setup>
let url = window.location.host
let ownerName = "Azis Ramadhan"
</script>

<template>
  <main>
    <h1>Hi there!</h1>
    <h2><span>{{ url }}</span> is owned by {{ ownerName }}</h2>
  </main>
</template>

<style scoped lang="scss">
main {
  height: 100vh;
  height: 100svh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

span {
  color: coral;
}
</style>

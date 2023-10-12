<template>
  <div class="settings off">
    <button class="delete is-pulled-right" aria-label="close"></button>
    <p>Dark Mode</p>
    <input type="checkbox">
  </div>
</template>

<script>
export default{
  data() {
    return{

    }
  }
}
</script>

<style scoped>
.settings{
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
}
</style>
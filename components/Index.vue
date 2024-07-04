<template>
  <div class="msg">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Welcome to my website made in vue !!'
    }
  }
}
</script>

<style scoped>
.msg {
  color: aquamarine;
}
</style>

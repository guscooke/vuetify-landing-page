<template>
  <span class="go-back">
    <button @click="goBack">voltar</button>
  </span>
</template>

<script>
  export default {
    methods: {
      goBack() {
        return this.$router.go(-1);
      }
    }
  };
</script>

<style scoped>
  .go-back {
    display: flex;
    cursor: pointer;
  }

  button {
    border: 0;
  }
</style>
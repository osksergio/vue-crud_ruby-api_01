<template>
  <div>
    <h1>Posts</h1>

    <!-- Create or Post -->
    <input type="text" v-model="title" placeholder="Title" class="title-input" />
    <input type="text" v-model="body" placeholder="Body" class="body-input" />
  </div>
</template>

<script setup>
</script>

<style scoped>
  .title-input {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    border: 2px solid #ccc;
    background-color: #f8f8f8;
    color: #111;
    border-radius: 4px;
    resize: vertical;
  }

  .body-input {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    box-sizing: border-box;
    border: 2px solid #ccc;
    background-color: #f8f8f8;
    color: #111;
    border-radius: 4px;
    resize: vertical;
  }
</style>
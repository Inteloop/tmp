<script setup>
import TodoList from './components/TodoList.vue'
</script>

<template>
  <div class="app-container">
    <h1>Vue Todo App</h1>
    <TodoList />
  </div>
</template>

<style>
.app-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
  text-align: center;
  color: #2c3e50;
  margin-bottom: 30px;
}
</style>
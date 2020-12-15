<template>
  <div id="app" class="container">
    <TodoInput/>
    <TodoList/>

  </div>
</template>

<script>
import TodoInput from '@/components/todoInput';
import TodoList from '@/components/todoList';

export default {
  name: 'App',
  components: {
    TodoInput,
    TodoList

  }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

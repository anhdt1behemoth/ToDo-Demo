<template>
  <div id="app">
    <div class="container">
      <AddTodos/>
      <FilterTodo/>
      <TodosDemo/>
    </div>
  </div>
</template>

<script>
import TodosDemo from './components/TodosDemo.vue'
import AddTodos from './components/AddTodo.vue'
import FilterTodo from './components/FilterTodo.vue'
export default {
  name: 'App',
  components: {
    TodosDemo,
    AddTodos,
    FilterTodo
  }
}
</script>

<style>

</style>

<template>
  <div>
    <h1>To-Do List</h1>
    <div>
      <TodoNew />
      <TodoList />
    </div>
  </div>
</template>

<script>
import TodoNew from "@/components/ToDoNew.vue";
import TodoList from './components/ToDoList.vue';

export default {
  components: {
    TodoNew,
    TodoList
  }
};
</script>

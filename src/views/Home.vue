<template>
  <div class="home">
    <img alt="Vue logo" class="logo" src="../assets/logo.png" />
    <Todo msg="Welcome to Your Vue.js App" />
    <TodoList />
  </div>
</template>

<script>
// @ is an alias to /src
import Todo from "@/components/Todo.vue";
import TodoList from "@/components/TodoList.vue";

export default {
  name: "Home",
  components: {
    Todo,
    TodoList
  }
};
</script>

<template>
  <div class="home">
    <Todo msg="todos" />
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

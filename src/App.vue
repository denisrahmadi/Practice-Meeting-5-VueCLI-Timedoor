<template>
  <div>
    <InputTodo></InputTodo>
    <!-- Start Todo List -->
    <TodoList></TodoList>
    <!-- End Todo List -->
  </div>
</template>
<script>
import InputTodo from "./components/InputTodo.vue";
import TodoList from "./components/TodoList.vue";

export default {
  components: {
    InputTodo,
    TodoList
  }
};
</script>
<style>
/** Body Style **/
body {
  font-family: "Open Sans", sans-serif;
}
/** Form Style **/

/** Start Todo List **/
/** End Todo List*/
</style>

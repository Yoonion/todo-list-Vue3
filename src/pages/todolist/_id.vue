<template>
  <h1>To-Do view page</h1>
  <TodoForm :editing="true" />
</template>

<script>
import TodoForm from '@/components/TodoForm.vue'

export default {
  components: {
    TodoForm
  }
}
</script>

<style>

</style>
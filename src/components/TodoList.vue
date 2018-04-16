<template>
    <div>
        <todo v-for="item in todos" :todo.sync="todo"></todo>
    </div>
</template>
<script>
import Todo from './Todo'

export default {
  name: 'TodoList',
  components: {
    Todo
  },
  props: ['todos']
}
</script>
<style>

</style>

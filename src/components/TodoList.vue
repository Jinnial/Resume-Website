<template>
    <div>
        <todo v-for="item in todos" :key="item"></todo>
    </div>
</template>
<script>
import Todo from "./components/Todo"

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

<template>
  <div id="app">
    <todo-list v-bind:todos="todos"></todo-list>
    <!-- <img src="./assets/logo.png"> -->
    <!-- <router-view/> -->
  </div>
</template>

<script>
import TodoList from './components/TodoList'

export default {
  name: 'App',
  components: {
    TodoList
  },
  // Send Data To Component
  data () {
    return {
      todos: [ {
        title: 'Todo A',
        project: 'Project A',
        done: false
      },
      {
        title: 'Todo B',
        project: 'Project B',
        done: false
      }]
    }
  }
}
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

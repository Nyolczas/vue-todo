<template>
  <div id="app">
   <Todos />
  </div>
</template>

<script>
import Todos from './components/Todos';

export default {
  name: 'app',
  components: {
   Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: "Első teendő",
          completed: false
        },
        {
          id: 2,
          title: "Második tennivaló",
          completed: false
        },
        {
          id: 3,
          title: "Harmadik teendő",
          completed: true
        }
      ]
    }
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Public+Sans:400,500,600,700,800,900&display=swap&subset=latin-ext');
  body {
    font-family: 'Public Sans', sans-serif;
  }
</style>

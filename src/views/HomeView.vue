<template>
  <div class="home">
    <AddTodo />
    <ToDo />
  </div>
</template>

<script>
// @ is an alias to /src
import ToDo from '@/components/ToDo.vue'
import AddTodo from '@/components/AddTodo.vue'

export default {
  name: 'HomeView',
  components: {
    ToDo,
    AddTodo
  }
};
</script>

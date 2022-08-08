<template>
  <div class="home">
    <AddTodo />
    <FilterTodos/>
    <ToDo />
  </div>
</template>

<script>
// @ is an alias to /src
import ToDo from '@/components/ToDo.vue'
import AddTodo from '@/components/AddTodo.vue'
import FilterTodos from '@/components/FilterTodos.vue'

export default {
  name: 'HomeView',
  components: {
    ToDo,
    AddTodo,
    FilterTodos
  }
};
</script>

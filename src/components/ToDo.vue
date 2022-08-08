<template>
  <div class="hello">
    <h3>Todos</h3>
    <div class="todos">
        <div v-for="todo in allTodos" :key="todo.id" class="todo">
            {{todo.title}}
        </div>
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex';

export default {
  name: 'ToDo',
  props: {
    msg: String
  },
  computed: mapGetters(['allTodos'])
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

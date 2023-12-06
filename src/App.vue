
<template>
  <div id="app">
    <todo></todo>
  </div>
</template>

<script>
import Todo from './components/Todo.vue'

export default {
  name: 'App',
  components:{
  Todo
}
}

</script>


<!-- 
// const todos = ref([]);
// const name = ref("");

// const input_content = ref("");
// const input_category = ref(null);

// const todos_asc = computed(() =>
//   todos.value.sort((a, b) => {
//     return b.createdAt - a.createdAt;
//   })
// ); -->
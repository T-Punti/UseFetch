<template>
  <h1>Users</h1>

</template>

<script>
import { UseFetch } from '../composable/UseFetch.js';

export default {
  setup(){
    const {data,error,loading} = UseFetch('https://jsonplaceholder.typicode.com/users',{});
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

<template>
  <div>
    <div class="row my-3 justify-content-between">
      <h3>{{todo.title}}</h3>
      <div>
        <button class="btn btn-primary mx-2">Edit</button>
        <button class="btn btn-danger">Delete</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props:{
    todo:{

    }
  }
};
</script>

<style lang="css" scoped>
</style>

<template>
  <h1>This is a Profile {{ $route.params.id }}</h1>
</template>

<style>
</style>

<script>
export default {
  validate({ params }) {
    return /^\d+$/.test(params.id);
  },
};
</script>
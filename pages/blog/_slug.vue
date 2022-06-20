<template>
  <div>
    <main v-if="$route.params.slug">
      <h1 v-text="'Blog Ready ' + $route.params.slug"></h1>
    </main>
    <main v-else>
      <h1>Block Cancel</h1>
    </main>
  </div>
</template>

<style>
</style>

<script>
export default {};
</script>
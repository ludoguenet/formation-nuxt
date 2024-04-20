<template>
  Project slug: {{ $route.params.projectSlug }}
  User id: {{ $route.params.userId }}
</template>

<script setup>
const route = useRoute();

console.log(route.params.projectSlug, route.params.userId);
</script>
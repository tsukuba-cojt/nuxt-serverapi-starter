<template>
  <div>
    {{ users }}
  </div>
</template>

<script setup>
const { data: users } = await useFetch('/api/users');
</script>

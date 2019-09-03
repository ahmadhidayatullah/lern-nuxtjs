<template>
  <h1>Hello, this is detail of user-id {{ $route.params.id }}</h1>
</template>

<script>
export default {
  validate(data) {
    return /^\d+$/.test(data.params.id);
  },
  layout: "user"
};
</script>
<template>
  <h1>{{ count }}</h1>
</template>

<script>
export default {
  data() {
    return {
      count: 2,
    };
  },
  created() {
    console.log("Created!");
  },
};
</script>

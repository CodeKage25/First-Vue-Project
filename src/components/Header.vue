<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <h1>{{ title }}</h1>
  <Button text="Add Task" color="green" />
</template>

<script>
import Button from "./Button";
export default {
  name: `"Header"`,
  props: {
    title: String,
  },
  components: {
    Button,
  },
};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>

<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <h1>{{ title }}</h1>
</template>

<script>
import Button from "./Button";
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Header",
  props: {
    title: String,
  },
  components: {
    // eslint-disable-next-line vue/no-unused-components
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

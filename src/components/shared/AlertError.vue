<template>
  <v-alert border="right" dismissible msg type="error"><slot></slot></v-alert>
</template>

<script>
export default {
  props: {
    msg: String,
  },
};
</script>

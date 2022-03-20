<template>
  <button class="button has-text-weight-semibold px-6">
    {{ content }}
  </button>
</template>

<script>
export default {
  name: "Button",
  props: {
    content: String,
  },
};
</script>
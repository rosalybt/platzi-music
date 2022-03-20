<template>
  <div id="textInput">
    <label
      class="
        third-color
        is-flex is-justify-content-flex-start
        has-text-weight-light
        is-size-6
        mt-4
      "
      >{{ labelName }}</label
    >
    <input class="input" type="text" />
  </div>
</template>





<script>
export default {
  name: "TextInputs",
  props: {
    labelName: String,
  },
};
</script>

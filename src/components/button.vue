<!--  -->
<template>
  <button class="hm-button">
    <span>
      <slot> </slot>
    </span>
  </button>
</template>

<script>
export default {
  name: "HmButton",
  props: {
    type: {
      type: String,
      default: "default",
    },
  },
  data() {
    return {};
  },
  computed: {},
  watch: {},
  methods: {},
};
</script>

<style scoped>
.hm-button {
  color: red;
}
</style>

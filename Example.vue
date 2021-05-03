<template>
  <div>
    <p :class="cssClassArray">
      Learning CSS and style: Blue and monospace font
    </p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      cssClassArray: ["blue-text", "mono-text"],
    };
  },
};
</script>

<style scoped>
.mono-text {
  font-family: monospace;
}

.blue-text {
  color: blue;
}
</style>
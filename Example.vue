<template>
  <div>
    <p :style="styleObject">
      Learning CSS and style: Monospace font and big text
    </p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      styleObject: { fontSize: "2rem", fontFamily: "monospace" },
    };
  },
};
</script>

<style scoped>
</style>
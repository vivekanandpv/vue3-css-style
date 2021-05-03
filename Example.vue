<template>
  <div>
    <p :style="[firstStyle, secondStyle]">
      Learning CSS and style: Monospace font and big text
    </p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      firstStyle: { fontSize: "2rem", fontFamily: "monospace" },
      secondStyle: { color: "green", backgroundColor: "yellow" },
    };
  },
};
</script>

<style scoped>
</style>
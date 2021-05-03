<template>
  <div>
    <p :class="enabledMono ? 'mono-text' : 'blue-text'">
      Learning CSS and style: Monospace font
    </p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      enabledMono: true,
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
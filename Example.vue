<template>
  <div>
    <p :class="[enabledMono ? 'mono-text' : 'blue-text', 'big-text']">
      Learning CSS and style: Monospace font and big text
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

.big-text {
  font-size: 2rem;
}
</style>
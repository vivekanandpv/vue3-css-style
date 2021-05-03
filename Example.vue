<template>
  <div>
    <p :class="{ 'red-text': enableRed }">Learning CSS and style: Red?</p>
    <p :class="{ 'blue-text': enableBlue }">Learning CSS and style: Blue?</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      enableRed: true,
      enableBlue: false,
    };
  },
};
</script>

<style scoped>
.red-text {
  color: red;
}

.blue-text {
  color: blue;
}
</style>
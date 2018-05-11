<template>
  <div>
    <img :src="src" width="100" />
  </div>
</template>

<script>
export default {
  props: {
    src: String
  }
}
</script>

<style scoped>
img {
  margin: 16px 0 16px 16px;
}
</style>

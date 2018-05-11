<template>
  <section class="container">
    <GirlImage :src="require('~/assets/icon_madoka.png')" />
    <GirlImage :src="require('~/assets/icon_homura.png')" />
    <GirlImage :src="require('~/assets/icon_kyoko.png')" />
    <GirlImage :src="require('~/assets/icon_sayaka.png')" />
    <GirlImage :src="require('~/assets/icon_mami.png')" />
  </section>
</template>

<script>
import GirlImage from '~/components/GirlImage.vue'

export default {
  components: {
    GirlImage
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

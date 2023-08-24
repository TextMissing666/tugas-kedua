<template>
  <div id="app">
    <headerWeb />
    <Nuxt />
    <footerWeb />
  </div>
</template>
<script>
// Memanggil component sesuai lokasi masing - masing file
import Header from '@/components/headerWeb.vue'
import Footer from '@/components/footerWeb.vue'
export default {
  // Dideklarasikan agar dapat diakses oleh template
  components: {
    Header,
    Footer,
  },
}
</script>
<style></style>

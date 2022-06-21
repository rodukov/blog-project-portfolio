<template>
  <div class="home">
    <welcome/>
    <about_items/>
    <socials/>
    <footers/>
  </div>
</template>

<script>
import welcome from '../components/welcome.vue'
import about_items from '../components/about_items.vue'
import socials from '../components/socials.vue'
import footers from '../components/footers.vue'
export default {
  name: 'Home',
  components: { welcome, about_items, socials, footers },
  mounted() { document.title = `My Blog ${ new Date().getFullYear() }` }
}
</script>
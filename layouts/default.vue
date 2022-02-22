<template>
  <div>
    <nav-bar />
    <nuxt />
  </div>
</template>

<script>
import NavBar from '~/components/NavBar.vue'

export default {
  components: {
    'nav-bar': NavBar,
  },
}
</script>

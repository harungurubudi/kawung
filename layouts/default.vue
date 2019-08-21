<template>
  <div>
    <site-header />
    <nuxt />
  </div>
</template>

<script>
import SiteHeader from '~/components/organisms/SiteHeader'

export default {
  components: {
    SiteHeader
  },
  head() {
    return {
      htmlAttrs: {
        lang: 'en',
      }
    }
  }
}
</script>
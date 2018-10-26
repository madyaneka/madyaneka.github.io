<template>
  <div>
    <app-navigation/>
    <nuxt/>
  </div>
</template>

<script>
import Navigation from '~/components/Navigation/Navigation'

export default {
  components: {
    appNavigation: Navigation
  }
}
</script>

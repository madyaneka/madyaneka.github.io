<template>
  <div>
    <app-navigation/>
    <section class="section">
      <nuxt/>
    </section>
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

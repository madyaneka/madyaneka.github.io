<template>
  <div>
    <app-navigation/>
    <section class="section">
      <div class="container">
        <nuxt/>
      </div>
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

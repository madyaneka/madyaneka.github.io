<template>
  <nav
    class="navbar is-dark"
    role="navigation"
    aria-label="main navigation">
    <div class="container">
      <div
        class="navbar-brand">
        <nuxt-link
          to="/"
          class="navbar-item">Home</nuxt-link>

        <a
          :class="{ 'is-active': isToggleActive }"
          role="button"
          class="navbar-burger"
          data-target="navbar-menu"
          aria-label="menu"
          aria-expanded="false"
          @click="isToggleActive = !isToggleActive">
          <span aria-hidden="true"/>
          <span aria-hidden="true"/>
          <span aria-hidden="true"/>
        </a>
      </div>

      <div
        :class="{ 'is-active': isToggleActive }"
        class="navbar-menu">
        <div class="navbar-start">
          <nuxt-link
            to="/blog"
            class="navbar-item"
            active-class="is-active">
            Blog
          </nuxt-link>
          <nuxt-link
            to="/about"
            class="navbar-item"
            active-class="is-active">
            About
          </nuxt-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isToggleActive: false
    }
  }
}
</script>

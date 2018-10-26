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
          role="button"
          class="navbar-burger"
          aria-label="menu"
          aria-expanded="false">
          <span aria-hidden="true"/>
          <span aria-hidden="true"/>
          <span aria-hidden="true"/>
        </a>
      </div>

      <div class="navbar-menu">
        <div class="navbar-start">
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

<template>
  <div>
    <div class="card">
      <header class="card-header">
        <div class="card-header-title">Title</div>
        <router-link
          :to="'/blog/' + identity"
          class="card-header-icon"
          aria-label="more options">
          <span class="icon">
            <i class="fas fa-info-circle"/>
          </span>
          {{ identity }}
        </router-link>
      </header>
      <div class="card-content">Akulah Arjunaaaaaaaa!!!</div>
    </div>
    <br>
  </div>
</template>

<script>
export default {
  props: {
    identity: {
      type: [ Number, String ],
      default: 0
    }
  }
}
</script>

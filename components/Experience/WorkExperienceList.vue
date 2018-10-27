<template>
  <section class="hero is-warning">
    <div class="hero-body">
      <div class="columns">
        <div
          v-for="experience in 2"
          :key="experience"
          class="column is-half">
          <app-work-experience/>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import WorkExperience from '~/components/Experience/WorkExperience'

export default {
  components: {
    appWorkExperience: WorkExperience
  }
}
</script>

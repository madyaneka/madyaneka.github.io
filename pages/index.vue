<template>
  <div class="columns">
    <div class="column">
      <section class="hero is-warning">
        <div class="container">
          <div class="hero-body">
            <h1 class="title">Madyan Eka Septian</h1>
            <h2 class="subtitle">Kediri, East Java, Indonesia</h2>
          </div>
        </div>
      </section>
      <hr>
      <app-proficiency/>
      <hr>
      <app-work-experience/>
    </div>
  </div>
</template>

<script>
import Proficiency from '~/components/Portfolio/Proficiency'
import WorkExperience from '~/components/Experience/WorkExperience'

export default {
  components: {
    appProficiency: Proficiency,
    appWorkExperience: WorkExperience
  }
}
</script>

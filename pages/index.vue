<template>
  <div class="columns">
    <div class="column">
      <section class="hero is-success">
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
      <app-work-experience-list/>
    </div>
  </div>
</template>

<script>
import Proficiency from '~/components/Portfolio/Proficiency'
import WorkExperienceList from '~/components/Experience/WorkExperienceList'

export default {
  components: {
    appProficiency: Proficiency,
    appWorkExperienceList: WorkExperienceList
  }
}
</script>

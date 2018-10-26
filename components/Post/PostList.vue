<template>
  <div class="columns">
    <div class="column is-8 is-offset-2">
      <app-post-preview
        v-for="post in 5"
        :key="post"
        :identity="post"/>
    </div>
  </div>
</template>

<script>
import PostPreview from '~/components/Post/PostPreview'

export default {
  components: {
    appPostPreview: PostPreview
  }
}
</script>

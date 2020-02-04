<template>
  <div class="container">
    <h1>Home</h1>
    <div class="feed-container">
      <feed></feed>
    </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Feed from '~/components/Feed.vue'

export default {
  components: {
    Logo,
    Feed
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: block;
}
</style>

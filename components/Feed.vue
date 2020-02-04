<template>
  <div class="container">
    <h1>Feed</h1>
    <div class="info">
      <nuxt-link class="author" to="">
        Author Name
      </nuxt-link>
      <p>Wed Feb 5/2020</p>
    </div>
    <div class="feed-content">
      <nuxt-link class="read-more" to="">
        <h1 class="feed-title">Title1</h1>
        <p class="feed-description">description</p>
        <span>Read more...</span>
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    articles: [];
  }
};
</script>

<style scoped>
.container {
  display: block;
}
</style>

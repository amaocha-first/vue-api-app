<template>
  <div class="container">
    <h1 class="home">Home</h1>
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

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: block;
}

.home {
  text-align: center;
  color: #f38d68;
}

.feed-container {
  
}
</style>

<style>
body {
  font-family: "sans-serif";
}
</style>

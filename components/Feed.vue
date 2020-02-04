<template>
  <div class="container">
    <h1 class="top">記事一覧</h1>
    <div class="feed-container">
      <div class="info">
        <img
          id="author-img"
          src="https://static.productionready.io/images/smiley-cyrus.jpg"
          alt=""
        />
        <div class="author-container">
          <nuxt-link class="link author" to="">
            Author Name
          </nuxt-link>
          <span class="date">Wed Feb 5/2020</span>
        </div>
      </div>
      <div class="feed-content">
        <nuxt-link class="link feed" to="">
          <h1 class="feed-title">Title1</h1>
          <p class="feed-description">description</p>
          <span class="read-more">Read more...</span>
        </nuxt-link>
      </div>
    </div>

    <div class="feed-container">
      <div class="info">
        <img
          id="author-img"
          src="https://static.productionready.io/images/smiley-cyrus.jpg"
          alt=""
        />
        <div class="author-container">
          <nuxt-link class="link author" to="">
            Author Name
          </nuxt-link>
          <span class="date">Wed Feb 5/2020</span>
        </div>
      </div>
      <div class="feed-content">
        <nuxt-link class="link feed" to="">
          <h1 class="feed-title">Title1</h1>
          <p class="feed-description">description</p>
          <span class="read-more">Read more...</span>
        </nuxt-link>
      </div>
    </div>
    
    <div class="feed-container">
      <div class="info">
        <img
          id="author-img"
          src="https://static.productionready.io/images/smiley-cyrus.jpg"
          alt=""
        />
        <div class="author-container">
          <nuxt-link class="link author" to="">
            Author Name
          </nuxt-link>
          <span class="date">Wed Feb 5/2020</span>
        </div>
      </div>
      <div class="feed-content">
        <nuxt-link class="link feed" to="">
          <h1 class="feed-title">Title1</h1>
          <p class="feed-description">description</p>
          <span class="read-more">Read more...</span>
        </nuxt-link>
      </div>
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
  width: 60%;
  background-color: white;
}

h1 {
  font-size: 26px;
}

.feed-container {
  padding: 10px 15px;
  border-bottom: solid 1px #f3f3f3;
}

.top {
  border-bottom: solid 3px #f3f3f3;
  color: #f38d68;
}

.link {
  color: #373a3c;
  text-decoration: none;
}

#author-img {
  border-radius: 50%;
  width: 40px;
  height: 40px;
}

.author-container {
    margin-top: 7px;
    display: inline-block;
    vertical-align: top;
}

.author {
  color: #f38d68;
  margin-top: 0;
  display: block;
}

.info {
  padding-bottom: 5px;
  line-height: 90%;
  display: inline-block;
}

.date {
  font-size: 12px;
  color: #bbbbbb;
}

.feed-description {
  color: #999999;
  font-size: 15px;
}

.read-more {
  font-size: 12px;
  color: #bbbbbb;
}
</style>

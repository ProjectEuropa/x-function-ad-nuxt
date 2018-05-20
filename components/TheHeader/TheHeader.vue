<template>
  <header>
    <nav class="black" role="navigation">
        <div class="nav-wrapper container">
              <div class="ttf">
                  <a id="logo-container" href="/" class="brand-logo">x-function</a>
              </div>
              <div class="icons">
                <a href="https://twitter.com/M2_m_" target="_blank"><i class="fa fa-twitter-square icon-space" id="twitter-icon"></i></a>
                <a href="https://x-function-blog.netlify.com/" target="_blank"><i class="fa fa-rss-square icon-space" id="blog-icon"></i></a>
              </div>
          </div>
      </nav>
  </header>
</template>

<script>
export default {};
</script>


<style lang="scss" scoped>
.nav-wrapper {
  display: flex;
  justify-content: space-between;
  #logo-container {
    color: aquamarine;
  }
  #twitter-icon {
    color: #00aced;
    font-size: 2em;
  }
  #blog-icon {
    color: #f26522;
    font-size: 2em;
  }
  .icon-space {
    margin-left: 5px;
  }
}

@media (max-width: 768px) {
    #logo-container {
        left: 30%;
    }
}
</style>


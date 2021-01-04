<template>
  <div class="container">
    <div>
      <h1 class="title">Aillevia.com</h1>
      <!-- <Logo />
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div> -->

      <!-- <nuxt-link :to="localePath('index')">{{ $t('welcome') }}</nuxt-link>
      <nuxt-link :to="localePath('/')">{{ $t('welcome') }}</nuxt-link>
      <nuxt-link :to="localePath('index', 'en')">Homepage in English</nuxt-link>
      <nuxt-link :to="switchLocalePath('en')">English</nuxt-link>
      <nuxt-link :to="switchLocalePath('fr')">Français</nuxt-link> -->
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    // console.log('this locale default ', this.$i18n.locale)
  },
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

<template>
  <div class="top-level layout">
    <nav class="container">
      <nuxt-link to="/">
        Silas Onmbayugh
      </nuxt-link>
      <nuxt-link to="/about">
        About/Resume
      </nuxt-link>
    </nav>
    <main>
      <nuxt />
    </main>
    <footer class="container">
      <div class="content">
        <p>Be great to hear from you! Drop me a line below.</p>
        <button class="contact-action">
          silas@onsilas.com
        </button>
      </div>
      <div class="socials">
        <a href="#"><img src="/svg/linkedin.svg" alt="linkedin"></a>
        <a href="#"><img src="/svg/dribbble.svg" alt="dribble"></a>
        <a href="#"><img src="/svg/twitter.svg" alt="twitter"></a>
        <a href="#"><img src="/svg/instagram.svg" alt="instagram"></a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>

<style lang="scss" src="./default.scss" scoped />

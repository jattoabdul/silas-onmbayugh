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
        <a
          href="mailto:silas@onsilas.com"
          target="_blank"
          class="contact-action"
        >
          silas@onsilas.com
        </a>
      </div>
      <div class="socials">
        <a href="https://linkedin.com/in/silasonmbayugh/" target="_blank"><img src="/svg/linkedin.svg" alt="linkedin"></a>
        <a href="https://dribbble.com/onsylas" target="_blank"><img src="/svg/dribbble.svg" alt="dribble"></a>
        <a href="https://twitter.com/onsylas" target="_blank"><img src="/svg/twitter.svg" alt="twitter"></a>
        <a href="https://www.instagram.com/onsylas/" target="_blank"><img src="/svg/instagram.svg" alt="instagram"></a>
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

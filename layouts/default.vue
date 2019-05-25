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
        <a href="https://linkedin.com/in/silasonmbayugh/"><img src="/svg/linkedin.svg" alt="linkedin"></a>
        <a href="https://dribbble.com/onsylas"><img src="/svg/dribbble.svg" alt="dribble"></a>
        <a href="https://twitter.com/onsylas"><img src="/svg/twitter.svg" alt="twitter"></a>
        <a href="https://www.instagram.com/onsylas/"><img src="/svg/instagram.svg" alt="instagram"></a>
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

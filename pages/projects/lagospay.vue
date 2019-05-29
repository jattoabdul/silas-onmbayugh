<template>
  <div class="child-level lgpay layout">
    <header>
      <nav class="container">
        <nuxt-link to="/" class="active">
          Silas Onmbayugh
        </nuxt-link>
        <nuxt-link to="/about">
          About/Resume
        </nuxt-link>
      </nav>
      <div class="header-project-detail-wrapper container">
        <div class="header-project-detail">
          <h2>LagosPay</h2>
          <p>
            <span class="title">Date:</span>
            <span class="value"> October 2018</span>
          </p>
          <p>
            <span class="title">Role:</span>
            <span class="value"> Product Design</span>
          </p>
        </div>
        <div class="header-project-detail-image">
          <div />
        </div>
      </div>
    </header>
    </nav>
    <main>
      <div class="page container lgpay">
        <h2 class="title short">
          Sorry, but this project is protected <br> Please contact me for access.
        </h2>
        <p class="subtitle short active">
          <span class="active">
            <span>Shoot me a mail:</span>
            <a href="mailto:silas@onsilas.com" target="_blank">silas@onsilas.com</a>
          </span>
        </p>

        <div class="description-action">
          <nuxt-link to="/" class="btn dark">
            Take me home
          </nuxt-link>
          <nuxt-link to="/projects/gorgeous-card" class="active">
            Next Project
            <span>
              <img src="/svg/arrow-right.svg" alt="next project">
            </span>
          </nuxt-link>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  layout: 'single',
  head: {
    title: 'Silas Onmbayugh - LagosPay'
  },
  components: {}
}
</script>

<style lang="scss" src="./projects.scss" scoped />

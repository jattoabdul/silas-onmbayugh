<template>
  <div class="child-level layout">
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
          <h2>FX Mallam</h2>
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
          <!-- <img src="/img/works/gc.png" alt="gorgeous cards"> -->
        </div>
      </div>
    </header>
    </nav>
    <main>
      <div class="page container gc">
        <h1 class="title">
          FX Mallam Page
        </h1>
        <h2 class="subtitle">
          A personal website and portfolio
        </h2>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  layout: 'single',
  head: {
    title: 'Silas Onmbayugh - FX Mallam'
  },
  components: {}
}
</script>

<style lang="scss" src="./projects.scss" scoped />

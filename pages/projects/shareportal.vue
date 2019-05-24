<template>
  <div class="child-level layout">
    <nav class="container">
      <nuxt-link to="/">
        Silas Onmbayugh
      </nuxt-link>
      <nuxt-link to="/about">
        About/Resume
      </nuxt-link>
    </nav>
    <main>
      <div class="page container gc">
        <h1 class="title">
          Shareportal
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
    title: 'Silas Onmbayugh - Shareportal'
  },
  components: {}
}
</script>

<style lang="scss" src="./projects.scss" scoped />

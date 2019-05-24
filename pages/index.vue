<template>
  <div class="page container">
    <div class="about-me-header">
      <div class="about-me-box">
        <h2>Hi there, I’m <br> Silas Onmbayugh.</h2>
        <p>I take ideas and turn them into products that users love, while meeting business objectives.</p>
      </div>
    </div>
    <div class="selected-work">
      <header>
        <span>Selected Work</span>
      </header>
      <div class="works-wrapper grid equal-two">
        <div class="work-outline-image">
          <div class="image">
            <img :src="activeWork.imageLink" :alt="activeWork.slug">
          </div>
        </div>
        <div class="works">
          <div
            v-for="(work, workIndex) in allWorks"
            :key="workIndex"
            class="work"
            :class="{ active: activeWork.slug == work.slug }"
            @mouseover="setActiveWork(work)"
          >
            <div class="mobile-image">
              <img :src="work.imageLink" :alt="work.slug">
            </div>
            <header @click="gotoProjectDetail(work)">
              <span v-text="work.title" />
            </header>
            <p v-text="work.desc" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Silas Onmbayugh - Home'
  },
  components: {},
  data() {
    return {
      allWorks: [
        {
          title: 'Gorgeous Card',
          slug: 'gorgeous-card',
          desc: 'Gorgeous card employs the use of cards, a mobile and web app to help businesses manage customers, record purchases and reward returning/loyal customers.',
          imageLink: '/img/works/gc.png'
        },
        {
          title: 'Femi Hand Bag',
          slug: 'femi-hand-bag',
          desc: 'The FemiHandbags brand aims to capture a spirit of individuality which does not attempt to adhere to seasonal trends.',
          imageLink: '/img/works/fhb.png'
        },
        {
          title: 'FX Mallam',
          slug: 'fx-mallam',
          desc: 'FX Mallam is a Currency Exchange Platform where users can trade in either of 4 currencies with directly with other users on the platform.',
          imageLink: '/img/works/fxm.png'
        },
        {
          title: 'Shareportal',
          slug: 'shareportal',
          desc: 'Shareportal is a mobile and web platform that enables shareholders to manage their shareholdings.',
          imageLink: '/img/works/spsa.png'
        }
      ],
      activeWork: {
        title: 'Gorgeous Card',
        slug: 'gorgeous-card',
        desc: 'Gorgeous card employs the use of cards, a mobile and web app to help businesses manage customers, record purchases and reward returning/loyal customers.',
        imageLink: '/img/works/gc.png'
      }
    }
  },
  computed: {},
  mounted() {
    // this.$eventBus.$on('event-name', (payload) => {
    //   console.log('on-fire of event for event-name', { payload })
    // })
  },
  beforeDestroy() {
    // this.$eventBus.$off('event-name')
  },
  methods: {
    setActiveWork(work) {
      this.activeWork = work
    },
    gotoProjectDetail(work) {
      this.activeWork = work
      this.$router.push(`/projects/${work.slug}`)
    }
  }
}
</script>

<style lang="scss" src="./index.scss" scoped />

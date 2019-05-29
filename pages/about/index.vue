<template>
  <div class="page container">
    <div class="grid equal-two about-wrapper">
      <div class="about-me">
        <span class="about-header-title">About Me</span>

        <p>
          I’m a Digital Product Designer, currently living in Lagos, Nigeria. My passion for design started with writing about fashion design in a now defunct fashion magazine I co-founded with a friend and I haven’t stopped learning about design and technology since.
        </p>
        <p>
          When I’m not behind my computer, I enjoy watching and playing football,  trying out new food, listening to podcasts on just about everything and hanging out with friends.
        </p>
      </div>
      <div class="work-experience-wrapper">
        <a class="btn dark" href="https://docs.google.com/document/d/1nWUWLXVuySVkhK6pGVfNfNakk1mNp4EbTm81zvQa7dM" target="_blank">Download CV</a>
        <div class="work-experience">
          <div class="experience">
            <div class="work-detail">
              <span class="company-name">
                Sterling Bank
              </span>
              <span class="position-title">
                PRODUCT DESIGNER
              </span>
            </div>
            <div class="duration">
              <span>
                <span>May 2018</span> - <span>Present</span>
              </span>
            </div>
          </div>
          <div class="experience">
            <div class="work-detail">
              <span class="company-name">
                Paystack
              </span>
              <span class="position-title">
                UI/UX DESIGNER INTERN
              </span>
            </div>
            <div class="duration">
              <span>
                <span>April 2018</span> - <span>May 2018</span>
              </span>
            </div>
          </div>
          <div class="experience">
            <div class="work-detail">
              <span class="company-name">
                Jolly
              </span>
              <span class="position-title">
                UI/UX DESIGNER / CO-FOUNDER
              </span>
            </div>
            <div class="duration">
              <span>
                <span>January 2017</span> - <span>Present</span>
              </span>
            </div>
          </div>
          <div class="experience">
            <div class="work-detail">
              <span class="company-name">
                Gorgeous Card
              </span>
              <span class="position-title">
                UI/UX &amp; GRAPHICS DESIGNER
              </span>
            </div>
            <div class="duration">
              <span>
                <span>May 2015</span> - <span>April 2018</span>
              </span>
            </div>
          </div>
          <div class="experience">
            <div class="work-detail">
              <span class="company-name">
                Learning Impact
              </span>
              <span class="position-title">
                GRAPHICS DESIGNER (Remote)
              </span>
            </div>
            <div class="duration">
              <span>
                <span>May 2015</span> - <span>April 2018</span>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Silas Onmbayugh - About'
  },
  components: {},
  data() {
    return {}
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
    // newMethod() {}
  }
}
</script>

<style lang="scss" src="./about.scss" scoped />

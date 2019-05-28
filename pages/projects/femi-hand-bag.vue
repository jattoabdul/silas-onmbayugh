<template>
  <div class="child-level fmhb layout">
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
          <h2>FemiHandbags</h2>
          <p>
            <span class="title">Date:</span>
            <span class="value"> April  2019</span>
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
    <main>
      <div class="page fmhb">
        <div class="overview-section container">
          <h3 class="header-title">
            Overview
          </h3>
          <p class="description">
            The FemiHandbags brand aims to capture a spirit of individuality which does not attempt to adhere to seasonal trends. Perceived as works of art, the handbags are made from the finest leathers and inspired by simple, classic shapes and vintage-styled silhouettes.  Artisanal, handcrafted touches such as whipstitched sides, hand-stitched, rolled handles, and hand sewn straps have become synonymous with the FemiHandbags aesthetic.
          </p>
        </div>
        <div class="my-role-section dark container x2">
          <h3 class="header-title dark">
            My Role
          </h3>
          <p class="description">
            In a team of two, I was tasked with the design of FemiHandbags. The stateholders wanted the site to look chic and classy. It should also sell the brand as not just african but world class to be taken seriously.
          </p>
        </div>
        <div class="design-process-section container grid equal-two">
          <h3 class="header-title wide">
            Design Process
          </h3>
          <p class="description one wide">
            <span class="descripton-number">1</span>
            <span class="sub-header">Research</span> - The website had a sketching build that was running but not fully functional at the time we started working on the project. The first thing I did was to interview the relevant stakeholders and understand their pain points as concerning the old build of the website. It help me gather who the target users were. I use the information to build user personas and fill in the knowledge gap.
          </p>
          <div class="description-images wide">
            <img src="/img/fmhb/fmhb-1.jpg" alt="fmhb-screen-1">
            <img src="/img/fmhb/fmhb-2.jpg" alt="fmhb-screen-2">
          </div>
          <p class="description two">
            <span class="descripton-number">2</span>
            <span class="sub-header">Conceptualization:</span> - I created the information architecture to identify how the whole site would work. I showed it to my team to agree on the proposed flow of content/information on the site.
          </p>
          <p class="description three">
            <span class="descripton-number">3</span>
            <span class="sub-header">Wireframes</span> - I then moved on to wireframing and building prototypes for the website. I sketched on paper first, and designed a low fidelity mockup of the apps to be tested with users.
          </p>
          <p class="description four">
            <span class="descripton-number">4</span>
            <span class="sub-header">Usability Testing </span>
            <ul>
              <li>
                Lo-fi prototypes were tested with the stakeholders to get feedback on the functionality, content, and interactivity of the product.
              </li>
              <br>
              <li>
                Beta Testing -  Before releasing the website, we’ll test it with potential users to fix any usability issues that’ll come up.
              </li>
            </ul>
          </p>
          <p class="description five">
            <span class="descripton-number">5</span>
            <span class="sub-header">Results</span> - After implenting the feedback collected from testing and the team was satisfied, I started with the visual design. The existing web and mobile app had many visible design flaws - from typography to the positioning of elements and after going through the process this was the end result.
          </p>
        </div>
        <div class="app-showcase-section">
          <div class="final-mockup">
            <h3 class="container showcase-header">
              Final Mockup
            </h3>
            <div class="container s2 bag-showcase-images">
              <img class="bag-showcase-img first" src="/img/fmhb/fmhb-sc-1.jpg" alt="fmhb-screen-1">
              <img class="bag-showcase-img" src="/img/fmhb/fmhb-sc-2.jpg" alt="fmhb-screen-2">
              <img class="bag-showcase-img" src="/img/fmhb/fmhb-sc-3.jpg" alt="fmhb-screen-3">
              <img class="bag-showcase-img" src="/img/fmhb/fmhb-sc-4.jpg" alt="fmhb-screen-4">
              <img class="bag-showcase-img" src="/img/fmhb/fmhb-sc-5.jpg" alt="fmhb-screen-5">
              <img class="bag-showcase-img" src="/img/fmhb/fmhb-sc-6.jpg" alt="fmhb-screen-6">
              <img class="bag-showcase-img" src="/img/fmhb/fmhb-sc-7.jpg" alt="fmhb-screen-7">
            </div>
          </div>
        </div>
        <div class="reflection-section container">
          <h3 class="header-title">
            Reflections
          </h3>
          <p class="description">
            Through the project,my delief that simple doesn’t have to mean dull was reaffirmed. FemiHandbags are very colorful pieces, theming the website off the dark brown from the logo gave the bright bags a solid background to showcase their beauty off of.
          </p>
          <p class="description">
            Showing the designs to the client and getting their feedback early can never be overstated, getting them to sign off on a design direction pays off in the end.
          </p>
          <div class="description-action">
            <nuxt-link to="/" class="btn dark">
              Take me home
            </nuxt-link>
            <nuxt-link to="/projects/fx-mallam" class="active">
              Next Project
              <span>
                <img src="/svg/arrow-right.svg" alt="next project">
              </span>
            </nuxt-link>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  layout: 'single',
  head: {
    title: 'Silas Onmbayugh - Femi Hand Bag'
  },
  components: {}
}
</script>

<style lang="scss" src="./projects.scss" scoped />

<template>
  <section class="workbox">
    <div class="container workbox__layout">
      <div class="workbox__text">
        <h1 class="title">Work</h1>
        <h2 class="subtitle">Experience</h2>
        <p>
          My professional experience includes using programming languages such
          as HTML, CSS, and JavaScript to create various features for client
          websites. I also have experience in developing and managing SQL
          databases. As a Web Developer, I have developed both the functional
          and aesthetic components of client websites. I believe I can make an
          immediate impact on your organization with my unique blend of skills
          and passion.
        </p>
      </div>
      <div class="workbox-gallery">
        <g-image
          class="workbox-gallery__center"
          alt="doneddy.dev"
          src="~/assets/images/Blackwell_heating.jpg"
        ></g-image>
        <g-image
          class="workbox-gallery__center"
          alt="doneddy.dev"
          src="~/assets/images/prsautohaus.com_.jpg"
        ></g-image>
        <g-image
          class="workbox-gallery__center"
          alt="doneddy.dev"
          src="~/assets/images/rolandconst.com_.jpg"
        ></g-image>
        <g-image
          class="workbox-gallery__center"     
          alt="doneddy.dev"
          src="~/assets/images/marineswwii.com_.jpg"
        ></g-image>
        <g-image
          class="workbox-gallery__center"
          alt="doneddy.dev"
          src="~/assets/images/noise-mitigation-symposium.com__0.jpg"
        ></g-image>
        <g-image
          class="workbox-gallery__center"
          alt="doneddy.dev"
          src="~/assets/images/mccaycellars.com_.jpg"
        ></g-image>
        <g-image
          class="workbox-gallery__center"
          alt="doneddy.dev"
          src="~/assets/images/strong_as_steele.jpg"
        ></g-image>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.workbox {
  background-color: white;
  border-top: 20px #28a4dc solid;
  padding: var(--vertical-space) 0;
}
.workbox__layout {
  display: grid;
  column-gap: 3rem;
}

.workbox__text {
  color: var(--defaultPrimaryOpposite);
  font-size: 1.6rem;
}

.workbox-gallery {
  grid-column: 1;
  grid-row-start: 1;
  display: grid;
  grid-gap: 3rem;
  grid-template-columns: 1fr;
}

.workbox-gallery__center {
  grid-column: 1;
  border: solid .25rem black;
}

/* large view */
@media(min-width:601px) {
  .workbox__layout {
        grid-template-columns: 1fr 1fr;
  }
  .workbox__text {
    grid-column-start: 2;
  }
} 

/* small view */
@media(max-width: 600px) {
  .workbox__layout {
        grid-template-columns: 1fr;
  }
  .workbox__text {
    grid-column-start: 1;
  }
}
</style>

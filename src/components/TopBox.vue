<template>
  <section class="topbox">
    <div class="container topbox__layout">
      <g-image
        class="topbox__self-image"
        alt="doneddy.dev"
        src="~/assets/images/headShot.jpg"
      ></g-image>
      <div class="topbox__text">
        <h1 class="title">D.A. Eddy</h1>
        <h3 class="subtitle">Designer & Developer</h3>
        <p class="bump-down">
          Front-end Web Developer with a focus on modern programming languages
          like HTML, CSS and JavaScript to design a quality user experience. Drupal site building and theming are also in my wheelhouse.
        </p>
        <SocialLinks class="topbox__social-links" />
      </div>
    </div>
  </section>
</template>

<script>
import SocialLinks from "~/components/SocialLinks";

export default {
  components: {
    SocialLinks,
  },
};
</script>

<style>
.topbox {
  background-image: url("~@/assets/images/topbackground.jpg");
  background-attachment: scroll;
  background-repeat: no-repeat;
  background-position: top;
  background-size: cover;
}

.topbox__layout {
  display: grid;
  grid-template-columns: 1fr 2fr;
  column-gap: 2rem;
  padding: var(--vertical-space) 0 var(--vertical-space);
}

.topbox__self-image {
  grid-column: 1 / 2;
  border: solid 3px white;
  width: 12rem;
}

.topbox__text {
  grid-column: 2 / 3;
  font-size: 1rem;
  text-align: right;
}

.topbox__social-links {
  margin-top: 2rem;
}
</style>

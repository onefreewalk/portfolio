<template>
  <section class="resume-box container">
    <h1 class="title">Resume</h1>

    <g-link href="/DonEddyJr.pdf" target="_blank"
      >
      <g-image
        class="resume-image"
        alt="my resume"
        src="~/assets/images/resumeImage.jpg"
      >
      </g-image>
    </g-link>
    <h3 class="subtitle">My Experience</h3>
    <p class="bump-down">
      Please click the image to download my resume.
    </p>
  </section>
</template>

<script>
export default {};
</script>

<style>
.resume-box {
  color: var(--defaultPrimaryFont);
  text-align: right;
  margin-top: var(--vertical-space);
  height: 20rem;
}
.resume-image {
  float: left;
  max-width: 20%;
  margin-right: 2rem;
}
</style>

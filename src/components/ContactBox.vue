<template>
  <footer class="contact-box container">
    <h1 class="title">Contact Me</h1>
    <h3 class="subtitle">Reach Out</h3>
    <p class="bump-down">
      Thank you very much for taking the time to take a look at my site and
      examples.
    </p>
    <p>Please contact me here.</p>
    <a class="addressLink" href="mailto:don@doneddy.dev">Send email</a>
    <p class="copy">Copyright &#169; 2020 Don Eddy Jr</p>
  </footer>
</template>

<script>
export default {};
</script>

<style>
.contact-box {
  color: var(--defaultPrimaryFont);
  text-align: right;
  margin-top: var(--vertical-space);
  height: 30rem;
}
.copy {
  text-align: center;
  margin-top: 10rem;
}
.addressLink {
  color: var(--theme-blue);
}
</style>

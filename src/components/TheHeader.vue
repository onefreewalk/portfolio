<template>
  <header class="header">
    <nav class="nav">
      <a class="nav__link" href="#about">About</a>
      <a class="nav__link" href="#work">Work</a>
      <a class="nav__link" href="#resume">Resume</a>
      <a class="nav__link" href="#contact">Contact</a>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
.header {
  position: fixed;
  left: 0;
  top: 0;
  right: 0;
  z-index: 200;
  margin: 0 auto;
}

@media (min-width: 768px) {
  .header {
    display: flex;
    justify-content: end;
  }
}

.nav {
  display: flex;
  justify-content: space-evenly;
  background-color: rgba(0, 0, 0, 0.3);
}

.nav__link {
  color: var(--defaultPrimaryFont);
  font-size: 1.25rem;
  font-weight: 400;
  text-decoration: none;
  padding: 0.5rem;
}

@media (min-width: 768px) {
  .nav__link {
    font-size: 1.75rem;
    padding: 1rem;
  }
}

.nav__link:hover {
  text-decoration: none;
}

.nav__link:visited {
  color: var(--defaultPrimaryFont);
}

.nav__link:hover {
  color: var(--theme-blue);
}
</style>

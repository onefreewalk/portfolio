<template>
  <div class="social-links">
    <a
      href="https://github.com/onefreewalk/portfolio"
      class="social-links__item social-links--github"
      alt="GitHub Icon"
      target="_blank"
    ></a>
    <a
      href="https://www.drupal.org/u/onefreewalk"
      class="social-links__item social-links--drupal"
      alt="Drupal Icon"
      target="_blank"
    ></a>
    <a
      href="https://codepen.io/onefreewalk"
      class="social-links__item social-links--codepen"
      alt="CodePen Icon"
      target="_blank"
    ></a>
    <!-- <a
      href="https://www..com"
      class="social-links__item social-links--email"
      alt="Email Icon"
      target="_blank"
    ></a> -->
  </div>
  <!-- end of social links -->
</template>

<script>
export default {};
</script>

<style>
.social-links__item {
  margin: 0 0.5rem;
  padding: 1rem;
  height: 106px;
  width: 107px;
  background: url("~@/assets/images/social-sprite.png");
  background-repeat: no-repeat;
  background-position: 0 0;
  display: block;
  float: left;
  cursor: pointer;
}

.social-links--github {
  background-position: 0 0;
}
a.social-links--github:hover {
  background-position-y: -106px;
}
.social-links--drupal {
  background-position: -108px 0;
}
a.social-links--drupal:hover {
  background-position: -108px -113px;
}
.social-links--codepen {
  background-position: -218px 0;
}
a.social-links--codepen:hover {
  background-position: -218px -117px;
}
.social-links--email {
  background-position: -329px 0;
}
a.social-links--email:hover {
  background-position: -329px -120px;
}
</style>

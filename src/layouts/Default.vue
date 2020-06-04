<template>
  <div class="layout">
    <TheHeader />
    <slot />
  </div>
</template>

<static-query>
  query {
    metadata {
      siteName
    }
  }
</static-query>

<script>
import TheHeader from "~/components/TheHeader";

export default {
  components: {
    TheHeader,
  },
};
</script>

<style></style>

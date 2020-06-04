<template>
  <a v-if="address && show" :href="'mailto:' + address">{{ address }}</a>
</template>

<script>
export default {
  name: "HideEmail",
  data() {
    return {
      show: false,
    };
  },
  props: {
    prefix: String,
    suffix: String,
  },
  computed: {
    address() {
      if (this.prefix && this.suffix) {
        return this.prefix + "@" + this.suffix;
      } else {
        return false;
      }
    },
  },
  mounted() {
    // Show the email if this is the browser
    if (process.browser) {
      this.show = true;
    }
  },
};
</script>

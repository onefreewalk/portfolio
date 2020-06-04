<template>
  <Layout>
    <TopBox id="about"/>
    <WorkBox id="work"/>
    <ResumeBox id="resume"/>
    <ContactBox id="contact"/>
  </Layout>
</template>

<script>
  import TopBox from '~/components/TopBox'
  import WorkBox from '~/components/WorkBox'
  import ResumeBox from '~/components/ResumeBox'
  import ContactBox from '~/components/ContactBox'
  export default {
    components: {
      TopBox,
      WorkBox,
      ResumeBox,
      ContactBox,
    },

    metaInfo: {
      title: 'doneddy.dev'
    }
  }
</script>

<style>

</style>

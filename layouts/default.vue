<template>
  <div>
    <TheHeader />
    <main class="contents">
      <nuxt />
    </main>
    <TheFooter />
  </div>
</template>

<script>
import TheHeader from '~/components/common/TheHeader'
import TheFooter from '~/components/common/TheFooter'

export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>

<style scoped lang="scss">
  .contents {
    max-width: 600px;
    padding: 0 10px;
    margin: 0 auto;
  }
</style>

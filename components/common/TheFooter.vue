<template>
  <footer class="footer">
    © my-portfolio.
    <font-awesome-icon :icon="['fab', 'github-square']" />
    <font-awesome-icon :icon="['fab', 'facebook']" />
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">

  .footer {
    color: #eee;
    background-color: $color-deepgray;
    text-align: center;
    line-height: 30px;
  }
</style>

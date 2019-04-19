<template>
  <footer class="footer">
    <a href="https://github.com/kogamitsuhiro" target="_blank">
      <font-awesome-icon :icon="['fab', 'github-square']" />
    </a>
    <a href="https://www.facebook.com/actmitu" target="_blank">
      <font-awesome-icon :icon="['fab', 'facebook']" />
    </a>
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

    a {
      color: #eee;
    }
  }
</style>

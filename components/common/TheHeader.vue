<template>
  <header class="header">
    <div class="header-inner">
      <nuxt-link to="/">
        <img src="~/assets/img/NEGUSE_header.png" class="header-img">
      </nuxt-link>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">

  .header {
    background-color: $color-deepgray;
    color: #eee;
  }

  .header-inner {
    a {
      color: inherit;
    }
  }

  .header-img {
    height: 8vh;
  }
</style>

<template>
  <header class="header">
    <div class="header-inner">
      <nuxt-link to="/">
        <p>コガミツヒロのポートフォリオ「NEGUSE」</p>
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
  .header-inner {
    padding: 5px;

    a {
      text-decoration: none;
      color: #eee;
    }
  }
}
</style>

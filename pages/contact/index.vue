<template>
  <div class="page-contact">
    <section class="contact">
      <h2 class="section-title">
        コンタクト
      </h2>
      <ArticleBody>
        <p>ポートフォリオをご覧いただきありがとうございます。<br>お問い合わせは以下より承ります。</p>
      </ArticleBody>
    </section>
  </div>
</template>

<script>
import ArticleBody from '~/components/common/ArticleBody'

export default {
  head() {
    return {
      title: 'Contact'
    }
  },
  components: {
    ArticleBody
  }
}
</script>

<style scoped lang="scss">

</style>

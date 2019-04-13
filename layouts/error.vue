<template>
  <div class="layout-error">
    <section class="error">
      <h2 class="section-title">
        404
      </h2>
      <ArticleBody>
        <p>アクセスされたページは存在しないか、すでに削除されています。</p>
      </ArticleBody>
    </section>
  </div>
</template>

<script>
import ArticleBody from '~/components/common/ArticleBody'

export default {
  head() {
    return {
      title: '404'
    }
  },
  components: {
    ArticleBody
  }
}
</script>

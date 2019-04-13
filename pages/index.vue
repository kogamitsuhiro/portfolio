<template>
  <div class="page-index">
    <section class="about">
      <h2 class="section-title">
        Koga Mitsuhiro
      </h2>
      <div class="article-body">
        <img src="~/assets/img/portrait.jpg">
        <p>古賀光弘(コガミツヒロ)</p>
      </div>
    </section>

    <section class="works">
      <h2 class="section-title">
        Hello, World!
      </h2>
      <ArticleBody>
        <p>
          古賀光弘(コガミツヒロ)です。<br>
          <br>
          1994年うまれ、佐賀県出身。<br>
          フィリピン留学を経て、高知県にあるベンチャー企業に入社しました。<br>
          Reactを使ったチャットボットサービスの機能追加・保守・運用したり、GASで業務改善のスクリプト組んだり、WordPressでサイト構築したり、WEBサービスのテスト設計・デバックなどしてます。
        </p>
      </ArticleBody>
    </section>
  </div>
</template>

<script>
import ArticleBody from '~/components/common/ArticleBody'

export default {
  head() {
    return {
      title: 'Home'
    }
  },
  components: {
    ArticleBody
  }
}
</script>

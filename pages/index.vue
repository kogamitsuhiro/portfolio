<template>
  <div class="page-index">
    <section class="about">
      <ArticleBody>
        <div class="img-wrap">
          <img src="~/assets/img/portrait.jpg">
        </div>
        <div class="img-title">
          <h3>コガミツヒロ</h3>
        </div>
      </ArticleBody>
    </section>

    <section class="works">
      <h2 class="section-title">
        About me!
      </h2>
      <ArticleBody>
        <p>
          古賀光弘(コガミツヒロ)です。<br>
          <br>
          1994年うまれ、佐賀県出身。<br>
          フィリピン留学を経て、高知県にあるベンチャー企業に入社しました。<br>
          Reactを使ったチャットボットサービスの機能追加・保守・運用したり、GASで業務改善のスクリプト組んだり、WordPressでサイト構築したり、WEBサービスのテスト設計・デバックなどしてます。
        </p>
        <nuxt-link to="/about">
          >> コガミツヒロってどんな人？
        </nuxt-link>
      </ArticleBody>
    </section>

    <section class="contact">
      <h2 class="section-title">
        Please message!
      </h2>
      <ArticleBody>
        <p>ご依頼・お問い合わせは以下のメールアドレスより承ります。</p>
        <p>utirn.ame(あっとまーく)gmail.com</p>
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

<style lang="scss" scoped>
.about{
  margin: 50px 0;
  .img-wrap {
    text-align: center;
    img {
      border-radius: 50%;
      width: 15rem;
    }
  }

  .img-title {
    text-align: center;
  }
}

</style>

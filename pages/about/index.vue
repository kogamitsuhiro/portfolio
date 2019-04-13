<template>
  <div class="page-about">
    <section class="history">
      <h2 class="section-title">
        経歴
      </h2>
      <ArticleBody>
        <h3>2017年</h3>
        <ul>
          <li>入社 株式会社SHIFTPLUS</li>
          <li>事業立ち上げ BUY-T(ファッションブランド)</li>
          <li>留学 フィリピン</li>
          <li>卒業 新潟大学 工学部 電気電子工学科</li>
        </ul>
        <h3>2015年</h3>
        <ul>
          <li>3年次編入 新潟大学 工学部 電気電子工学科</li>
          <li>卒業 久留米高専 電気電子工学科</li>
        </ul>
        <h3>2010年</h3>
        <ul>
          <li>入学 久留米高専 電気電子工学科</li>
        </ul>
      </ArticleBody>
    </section>
    <section class="motivation">
      <h2 class="section-title">
        モチベーション・今やりたいこと
      </h2>
      <ArticleBody>
        <p>
          問題解決や業務改善のために技術を使うことにモチベーションを感じます。
          (「古賀くん、ここの問題どうにかならない？」と相談するとニヤニヤしてるらしいです。)<br>
          プログラミングは目的達成の”手段”としか思わない人間でしたが、<br>
          最近はスキルが少しづつ付いてきて、実現出来ることが増えることにもモチベーションを感じています。<br>
          貢献度が高く、スキルが身に付く事をやっていきたいです。
        </p>
      </ArticleBody>
    </section>
    <section class="skill">
      <h2 class="section-title">
        スキル
      </h2>
      <ArticleBody>
        <p>ES2015 / React / Vue / Nuxt / WordPress / Google Apps Script / AWS</p>
      </ArticleBody>
    </section>
    <section class="event">
      <h2 class="section-title">
        LT発表・イベント
      </h2>
      <ArticleBody>
        <ul>
          <li>2018.12 もくもく会せんかえ？ 開催</li>
          <li>2018.10 Mashup Awards 2018 高知予選  参加</li>
          <li>2018.8  OFF TOKYO DEEP Development パネルディスカッション</li>
          <li>2018.7  JAWS-UG 第8回勉強会 LT発表</li>
        </ul>
      </ArticleBody>
    </section>
  </div>
</template>

<script>
import ArticleBody from '~/components/common/ArticleBody'

export default {
  head() {
    return {
      title: 'About'
    }
  },
  components: {
    ArticleBody
  }
}
</script>

<style scoped lang="scss">

</style>

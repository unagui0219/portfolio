<template>
  <div class="about">
    <PageTitle title="About" />
    <div class="content">
      <!-- <div class="self-img_cover">
        <img class="self-img" />
      </div> -->
      <div class="self-text_cover">
        <h2>鰻渕勇斗(Unagibuchi Hayato)</h2>
        <div class="self-text">
          <p>初めまして。鰻渕勇斗と申します。</p>
          <p>
            2019年からプログラミング（最初はRuby）を学び始め、2020年9月にNOVERX合同会社を起業しました。
            趣味は、ゲーム（主にPS4,Switch）と読書（バイブルは「Zero to
            One」と「論語と算盤」）、お酒とコーヒーを飲むことです。
            音楽は基本的にどんなジャンルでも聴きます。 好きなアーティストは、
            <a href="https://music.apple.com/jp/artist/fkj/644688726">FKJ</a>や
            <a href="https://music.apple.com/jp/artist/BrunoMars/278873078">
              Bruno Mars </a
            >、 邦楽だと椎名林檎やずっと真夜中でいいのに、久保田利伸です。
            好きな食べ物はタコスとラーメン（最近は家系にハマってます）です。
          </p>
        </div>
        <div class="self-info">
          <p>Mail: unagibuchi.biz@gmail.com</p>
          <p>
            Instagram:
            <a href="https://www.instagram.com/im___eel713/"> @im___eel713 </a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import PageTitle from "@/components/PageTitle.vue";

export default {
  name: "About",
  components: {
    PageTitle,
  },
};
</script>

<style>
.self-text_cover {
  width: 70%;
  margin: 0 auto;
}
</style>

<template>
  <div>
    <Navbar />
    <Header />
    <div class="wrapper">
      <div class="wrapper-columns">
        <div class="wrapper-columns-right">
          <nuxt />
        </div>
        <div class="wrapper-columns-left">
          <div class="wrapper-columns-twitter">
            <a
              class="twitter-timeline"
              data-lang="ja"
              data-height="500"
              href="https://twitter.com/Gakuzyo_chan?ref_src=twsrc%5Etfw"
              >Tweets by Gakuzyo_chan</a
            >
            <script
              async
              src="https://platform.twitter.com/widgets.js"
              charset="utf-8"
            ></script>
          </div>
          <p>
            <a href="https://twitter.com/Gakuzyo18Kin" target="blank"
              ><img
                src="../assets/img/tw.png"
                class="social"
              />R18のTwitterは…///こっち…///</a
            ><br />
            <a href="https://twitter.com/gakujochan_info" target="blank"
              ><img
                src="../assets/img/tw.png"
                class="social"
              />学情チャンプロジェクト（運営）</a
            ><br />
            <a
              href="https://marshmallow-qa.com/gakuzyo_chan?utm_medium=url_text&utm_source=promotion"
              target="blank"
              ><img
                src="../assets/img/mqa.png"
                class="social"
              />学情チャンのマシュマロ</a
            ><br />
            <a
              href="https://www.youtube.com/channel/UCw2JBhwHg-YXycBYx6ZI1bQ"
              target="blank"
              >学情チャンのYouTubeチャンネル</a
            >
          </p>
          <br />
          <a
            href="https://addons.mozilla.org/ja/firefox/addon/%E5%AD%A6%E6%83%85%E3%83%81%E3%83%A3%E3%83%B3%E3%81%AE%E3%83%86%E3%83%BC%E3%83%9E/"
            target="blank"
          >
            <img src="../assets/img/fx.png" /> </a
          ><br />
          <a href="https://typing.twi1.me/game/153670" target="blank">
            <img src="../assets/img/typing.png" /> </a
          ><br />
          <p>このページを宣伝してね！</p>
          <p>
            <a
              href="https://twitter.com/share?ref_src=twsrc%5Etfw"
              class="twitter-share-button"
              data-size="large"
              data-show-count="false"
              >Tweet</a
            >
            <script
              async
              src="https://platform.twitter.com/widgets.js"
              charset="utf-8"
            ></script>
          </p>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";
export default {
  name: "IndexPage",
  components: { Navbar, Header, Footer },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  font-family: "Noto Sans JP", sans-serif;
  font-size: 14px;
  line-height: 20px;
}

.navbar,
.header,
.wrapper {
  width: 950px;
  margin: auto;
}

.wrapper h1 {
  margin-top: 16px;
  margin-bottom: 20px;
  padding: 6px 0;
  font-size: 26px;
  font-weight: bold;
  color: #0063b1;
  line-height: 32px;
  border-bottom: solid 3px #0063b14d;
}

.wrapper h2 {
  margin: 18px 0;
  padding: 6px 0;
  font-size: 20px;
  font-weight: bold;
  color: #0063b1;
  line-height: 24px;
  border-bottom: solid 2px #0063b14d;
}

.wrapper h3 {
  margin-top: 24px;
  margin-bottom: 12px;
  font-size: 16px;
  font-weight: bold;
  color: #0063b1;
  line-height: 24px;
}

.wrapper ul {
  margin: 14px;
}

.wrapper li {
  font-size: 18px;
  margin: 8px 5px;
}

.wrapper p {
  margin: 10px 0;
  font-size: 14px;
  line-height: 22px;
  color: #333;
}

.wrapper hr {
  margin: 10px 0;
  border-top: solid 1px #0063b14d;
}
</style>

<template>
  <div class="footer">
    <div class="wrapper">
      <p>
        注意：このウェブサイトは学務情報システムに関連する大学・企業・その他機関とは一切関係ありません。<br />
        This website is not affiliated with any university, company, or other
        institution related to student affairs system (Gakujo system).
      </p>
      <p>
        (c) 2021,2022 学情チャンプロジェクト all rights reserved.<br />
        Website and graphic design :
        <a href="https://arkw.net/" target="blank">Sora Arakawa</a><br />
        Maintenance and administration :
        <a href="https://ghevp.com/" target="blank">ぐゑ</a>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  padding-top: 27px;
  padding-bottom: 20px;
  color: #fff;
  background: linear-gradient(#0063b1, #0078d7);
  text-shadow: 0 0 2px #333;
}

.footer a,
.footer p {
  color: #fff;
}

@media screen and (max-width: 1023px) {
  .wrapper {
    width: 100%;
  }

  .footer {
    padding-top: 40px;
  }
}
</style>

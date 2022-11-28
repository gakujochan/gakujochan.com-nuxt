<template>
  <div class="navbar">
    <div class="navbar-left">
      <a href="index.php"><img src="../assets/img/logo.png" /></a>
    </div>
    <div class="navbar-right">
      <ul>
        <a href="index.php?p=reference"><li>資料集</li></a>
        <a href="index.php?p=song"><li>うた</li></a>
        <a href="index.php?p=rules"><li>学情チャンとのお約束</li></a>
        <a href="index.php?p=contest"><li>コンテスト</li></a>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.navbar {
  margin-top: 20px;
  margin-bottom: 15px;
  position: relative;
  box-sizing: border-box;
  overflow: hidden;
}

.navbar-left img {
  width: 300px;
}

.navbar-right {
  width: 700px;
  float: right;
  text-align: right;
}

.navbar-right ul {
  position: absolute;
  top: 40px;
  right: 0;
  overflow: hidden;
  list-style-type: none;
}

.navbar-right a {
  color: #0078d7;
}

.navbar-right li {
  margin-left: 40px;
  font-size: 18px;
  float: left;
}

.navbar-right li:hover {
  opacity: 0.7;
}

@media screen and (max-width: 1023px) {
  .navbar,
  .navbar-left,
  .navbar-right {
    width: 100%;
  }

  .navbar {
    position: static;
  }

  .navbar-left {
    padding-bottom: 8px;
    text-align: center;
  }

  .navbar-right {
    margin-top: 10px;
    float: none;
    overflow: hidden;
    background: linear-gradient(#0063b1, #0078d7);
  }

  .navbar-right ul {
    position: static;
    text-align: center;
    padding-left: 0;
  }

  .navbar-right a {
    color: #fff;
  }

  .navbar-right li {
    margin-left: 0;
    padding: 0 20px;
    padding-top: 10px;
    padding-bottom: 12px;
  }
}

@media screen and (max-width: 749px) {
  .navbar-right li {
    width: 100%;
    margin-left: 0;
    padding: 10px 0;
    background: linear-gradient(#0063b1, #0078d7);
    border-bottom: solid 1px #ffffffb3;
  }
}

@media screen and (max-width: 499px) {
  .navbar-left img {
    width: 70%;
  }
}
</style>

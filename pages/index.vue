<template>
  <div>
    <Navbar />
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";
import Header from "~/components/Header.vue";
import Main from "~/components/Main.vue";
import Footer from "~/components/Footer.vue";
export default {
  name: "IndexPage",
  components: { Navbar, Header, Main, Footer },
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

<template>
<HeaderTop/>
</template>

<script>
import { Options, Vue } from "vue-class-component";
import HeaderTop from './components/HeaderTop.vue'

@Options({
  components: {
    HeaderTop,
  }
})
export default class App extends Vue {}
</script>

<style>
@font-face {
  font-family: "Pretendard-Medium";
  src: url("https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Medium.woff")
    format("woff");
  font-weight: 500;
  font-style: normal;
}
@font-face {
  font-family: "Pretendard-Bold";
  src: url("https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Bold.woff")
    format("woff");
  font-weight: 700;
  font-style: normal;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
* {
  font-family: "Pretendard-Medium";
  font-size: 12px;
  color: #090909;
  box-sizing: border-box;
  margin: 0 auto;
  text-decoration: none;
  font-style: normal;
  list-style: none;
}
</style>

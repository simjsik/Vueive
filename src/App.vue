<template>
  <HeaderTop />
  <main id="main">
    <section id="product">
      <div class="main_visual_wrap">
        <a class="visual_link_wrap"></a>
        <div class="main_visual_text_box">
          <span>VIVE 가정의 달</span>
          <p>가정의 달을 맞아 온 가족이 함께 VR을 즐기세요.</p>
        </div>
        <div class="visual_img_wrap"></div>
        <div class="visual_button">
          <button>쇼핑하기</button>
        </div>
      </div>
      <!-- main visual -->
      <div class="vive_elite_wrap">
        <a class="elite_link_wrap"></a>
        <div class="vive_elite_text_box">
          <span>VIVE XR Elite</span>
          <p>가벼운 무게. 가벼운 탄소 배출량.</p>
        </div>
        <div class="elite_img_wrap"></div>
        <div class="elite_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- vive elite -->
      <div class="vive_tracker_wrap">
        <a class="tracker_link_wrap"></a>
        <div class="vive_tracker_text_box">
          <span>VIVE Ultimate Tracker</span>
          <p>어떠한 움직임에도 정밀하게.</p>
        </div>
        <div class="tracker_img_wrap"></div>
        <div class="tracker_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- vive tracker -->
    </section>
    <!-- product section -->

    <section id="promotion">
      <div class="xr_elite">
        <a class="xr_elite_link"></a>
        <div class="xr_elite_text_box">
          <span>VIVE XR Elite</span>
          <p>가벼운 무게. 가벼운 탄소 배출량. 환경을 위한 노력.</p>
        </div>
        <div class="xr_elite_img_wrap"></div>
        <div class="xr_elite_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- XR Elite -->
      <div class="flow">
        <a class="flow_link"></a>
        <div class="flow_text_box">
          <span>VIVE Flow</span>
          <p>심플하면서 고급스러운 VR글래스</p>
        </div>
        <div class="flow_img_wrap"></div>
        <div class="flow_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- Vive flow -->
      <div class="focus">
        <a class="focus_link"></a>
        <div class="focus_text_box">
          <span>VIVE Focus</span>
          <p>올인원 VR의 명작</p>
        </div>
        <div class="focus_img_wrap"></div>
        <div class="focus_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- Vive focus -->
      <div class="cosmos">
        <a class="cosmos_link"></a>
        <div class="cosmos_text_box">
          <span>VIVE Cosmos</span>
          <p>더 흥미롭고. 창의적으로.</p>
        </div>
        <div class="cosmos_img_wrap"></div>
        <div class="cosmos_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- Vive cosmos -->
      <div class="pro">
        <a class="pro_link"></a>
        <div class="pro_text_box">
          <span>VIVE Pro</span>
          <p>예리하게. 정확하게. 깊게.</p>
        </div>
        <div class="pro_img_wrap"></div>
        <div class="pro_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- Vive pro -->
      <div class="accessory">
        <a class="accessory_link"></a>
        <div class="accessory_text_box">
          <span>액세서리</span>
          <p>모험에 필요한 모든 것.</p>
        </div>
        <div class="accessory_img_wrap"></div>
        <div class="accessory_button">
          <button class="bt_more">더 알아보기</button>
          <button class="bt_buy">구입하기</button>
        </div>
      </div>
      <!-- accessory -->
    </section>
    <!-- promotion section -->
  </main>
</template>

<script>
import { Options, Vue } from "vue-class-component";
import HeaderTop from "./components/HeaderTop.vue";

@Options({
  components: {
    HeaderTop,
  },
})
export default class App extends Vue {}
</script>

<style>
@font-face {
  font-family: "Pretendard-Regular";
  src: url("https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-Regular.woff")
    format("woff");
  font-weight: 500;
  font-style: normal;
}
@font-face {
  font-family: "Pretendard-SemiBold";
  src: url("https://fastly.jsdelivr.net/gh/Project-Noonnu/noonfonts_2107@1.1/Pretendard-SemiBold.woff")
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
}
* {
  font-family: "Pretendard-Regular";
  font-size: 12px;
  color: #090909;
  box-sizing: border-box;
  margin: 0 auto;
  text-decoration: none;
  font-style: normal;
  list-style: none;
}
button:hover {
  cursor: pointer;
}
main {
  width: 100%;
  margin-top: 44px;
}
.main_visual_wrap {
  position: relative;
  width: 100%;
  height: 692px;
  background: #d6d6d6;
}
.main_visual_text_box {
  position: absolute;
  top: 470px;
  left: 50%;
  transform: translateX(-50%);
}
.main_visual_text_box > span {
  font-size: 52px;
  font-family: "pretendard-semibold";
}
.main_visual_text_box > p {
  font-size: 26px;
  margin-top: 10px;
}
.visual_button {
  position: absolute;
  bottom: 50px;
  left: 50%;
  transform: translateX(-50%);
}
.visual_button button {
  font-size: 16px;
  width: 104px;
  height: 44px;
  border-radius: 50px;
  border: none;
  background: #0071e3;
  color: #fff;
}
/* main visual */

.vive_elite_wrap {
  width: 100%;
  height: 692px;
  margin-top: 12px;
  background: #d6d6d6;
  position: relative;
}
.vive_elite_text_box {
  position: absolute;
  top: 60px;
  left: 50%;
  transform: translateX(-50%);
}
.vive_elite_text_box > span {
  font-size: 52px;
  font-family: "pretendard-semibold";
}
.vive_elite_text_box > p {
  font-size: 26px;
  margin-top: 10px;
}
.elite_button {
  position: absolute;
  top: 186px;
  left: 50%;
  transform: translateX(-50%);
}
.tracker_button {
  position: absolute;
  top: 186px;
  left: 50%;
  transform: translateX(-50%);
}

/* vive elite */

.vive_tracker_wrap {
  width: 100%;
  height: 692px;
  background: #d6d6d6;
  margin-top: 12px;
  position: relative;
}
.vive_tracker_text_box {
  position: absolute;
  top: 60px;
  left: 50%;
  transform: translateX(-50%);
}
.vive_tracker_text_box > span {
  font-size: 52px;
  font-family: "pretendard-semibold";
}
.vive_tracker_text_box > p {
  font-size: 26px;
  margin-top: 10px;
}
/* vive tracker */
.bt_more {
  width: 122px;
  height: 44px;
  background: #0071e3;
  border-radius: 50px;
  color: #fff;
  border: none;
  font-size: 16px;
  margin-right: 10px;
}
.bt_buy {
  width: 104px;
  height: 44px;
  background: none;
  border-radius: 50px;
  color: #0071e3;
  border: 1px solid #0071e3;
  font-size: 16px;
}
/* product section */

#promotion {
  width: 100%;
  padding: 0px 0px 0px 12px;
}
#promotion > div {
  position: relative;
  width: calc(50% - 12px);
  height: 580px;
  margin-right: 12px;
  float: left;
}
.xr_elite_img_wrap {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: #000;
}
.xr_elite_text_box span,
.xr_elite_text_box p {
  color: #fff;
}

/* elite */
.flow_img_wrap {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: #f5f5f7;
}
/* flow */
.focus{
  margin-top: 12px;
}
.focus_img_wrap {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  background: #000;
}
.focus_text_box span,
.focus_text_box p {
  color: #fff;
}
/* focus */
.cosmos{
  margin-top: 12px;
}
.cosmos_img_wrap {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  background: #000;
}
.cosmos_text_box span,
.cosmos_text_box p {
  color: #fff;
}
/* cosmos */
.pro{
  margin-top: 12px;
}
.pro_img_wrap {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  background: #FCFCFD;
}
/* pro */
.accessory{
  margin-top: 12px;
}
.accessory_img_wrap {
  position: absolute;
  top: 0;
  width: 100%;
  height: 100%;
  background: #F9F9FB;
}
/* accessory */
.xr_elite_text_box,
.focus_text_box,
.flow_text_box,
.cosmos_text_box,
.pro_text_box,
.accessory_text_box {
  position: relative;
  z-index: 2;
  margin-top: 50px;
}
.xr_elite_text_box span,
.flow_text_box span,
.focus_text_box span,
.cosmos_text_box span,
.pro_text_box span,
.accessory_text_box span {
  font-size: 40px;
  font-family: "pretendard-semibold";
}
.xr_elite_text_box p,
.flow_text_box p,
.focus_text_box p,
.cosmos_text_box p,
.pro_text_box p,
.accessory_text_box p {
  font-size: 18px;
  margin-top: 6px;
}
.xr_elite_button,
.flow_button,
.focus_button,
.cosmos_button,
.pro_button,
.accessory_button {
  position: relative;
  margin-top: 20px;
}
#promotion .bt_more {
  font-size: 14px;
  width: 96px;
  height: 40px;
}
#promotion .bt_buy {
  font-size: 14px;
  width: 81px;
  height: 40px;
}
</style>

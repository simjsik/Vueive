<template>
  <header>
    <div class="header_wrap">
      <div class="header_logo">
      </div>
      <div class="header_menu_wrap">
        <div class="header_product"><a href="#">제품</a></div>
        <div class="header_viverse"><a href="#">VIVERSE</a></div>
        <div class="header_business"><a href="#">비즈니스</a></div>
        <div class="header_support"><a href="#">지원</a></div>
        <div class="header_community"><a href="#">커뮤니티</a></div>
        <div class="header_accesorry"><a href="#">액세서리</a></div>
      </div>
      <div class="header_right_menu">
        <div class="header_search"></div>
        <div class="header_basket"></div>
        <div class="header_profile"></div>
      </div>
    </div>
  </header>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({})
export default class HeaderTop extends Vue {
  msg!: string;
}
</script>

<style scoped>
header{
  position: fixed;
  top: 0px;
  left: 0px;
  width: 100%;
  height: 44px;
  background: #F9F9FB;
}
.header_wrap{
  width: 1000px;
  height: 44px;
  margin: 0 auto;
  background: yellow;
}

.header_logo{
  width: 44px;
  height: 100%;
  background: red;
  float: left;
}
.header_menu_wrap{
  float: left;
  margin-left: 100px;
}
.header_menu_wrap>div{
  float: left;
  margin-right: 72px;
  line-height: 44px;
}
.header_right_menu{
  float: right;
}
.header_right_menu>div{
  float: left;
  width: 44px;
  height: 44px;
  background: red;
  margin-right: 18px;
}
.header_right_menu>div:last-child{
  margin-right: 0px;
}
</style>

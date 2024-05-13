<template>
  <header>
    <nav>
      <div class="header_wrap">
        <div class="header_logo"></div>
        <ul class="header_menu_wrap">
          <li class="header_product"><a href="#">제품</a></li>
          <li class="header_viverse"><a href="#">VIVERSE</a></li>
          <li class="header_business"><a href="#">비즈니스</a></li>
          <li class="header_support"><a href="#">지원</a></li>
          <li class="header_community"><a href="#">커뮤니티</a></li>
          <li class="header_accesorry"><a href="#">액세서리</a></li>
        </ul>
        <ul class="header_right_menu">
          <li class="header_search"></li>
          <li class="header_basket"></li>
          <li class="header_profile"></li>
        </ul>
      </div>
    </nav>
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
header {
  position: fixed;
  top: 0px;
  left: 0px;
  width: 100%;
  height: 44px;
  background: #f9f9fb;
}
.header_wrap {
  width: 1000px;
  height: 44px;
  margin: 0 auto;
  background: yellow;
}

.header_logo {
  width: 44px;
  height: 100%;
  background: red;
  float: left;
}
.header_menu_wrap {
  float: left;
  margin-left: 72px;
}
.header_menu_wrap > li {
  float: left;
  margin-right: 72px;
  line-height: 44px;
}
.header_menu_wrap > li:last-child{
  margin-right: 0px;
}
.header_right_menu {
  float: right;
}
.header_right_menu > li {
  float: left;
  width: 44px;
  height: 44px;
  background: red;
  margin-right: 18px;
}
.header_right_menu > li:last-child {
  margin-right: 0px;
}
</style>

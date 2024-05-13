<template>
  <header>
    <div class="header_wrap">
      <div class="header_logo">
      </div>
      <div class="header_menu_wrap">
        <div class="header_product"></div>
        <div class="header_viverse"></div>
        <div class="header_business"></div>
        <div class="header_support"></div>
        <div class="header_community"></div>
        <div class="header_accesorry"></div>
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
</style>


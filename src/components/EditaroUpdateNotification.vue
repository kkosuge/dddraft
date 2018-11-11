<template>
  <div id="editaro-update-notification">
    <a href="https://editaro.com" target="_blank">
      dddraft は「エディ太郎」に変わりました。大変お手数ですが、再インストールが必要です。
    </a>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class extends Vue {}
</script>

<style lang='scss'>
#editaro-update-notification {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 22px;
  z-index: 1002;
  font-size: 12px;
  background: #f44336;
  color: #fff;
  text-align: center;
  a {
    color: #fff;
    display: block;
    padding: 8px 22px;
    text-decoration: none;
  }
}
</style>

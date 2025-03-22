<script setup lang="ts">
// defineProps<{
//
// }>()
</script>

<template>
  <footer class="py-5">
    <div>
      <div class="d-inline-block" style="width: 23%;">
        <!--                <h4><b>Elytra</b></h4>-->
        <img src="@/assets/img/elytra-lg-tint.png" style="height: 29px;">
        &nbsp; | &nbsp;
        <img src="@/assets/img/tx.png" style="height: 49px;">
      </div>

      <div class="footer-linkmap d-inline-block">
        <div>
          <span>Community</span>
          <a>IRC Channel</a>
        </div>
        <div>
          <span>Development</span>
          <a>Blogs</a>
          <a>Version History</a>
        </div>
        <div>
          <span>About</span>
          <a>FAQ</a>
        </div>
      </div>

      <hr class="my-4">

      <div>
        <div class="footer-right-decls float-end text-muted fs-small">
          <a>Terms of Use</a>
          <a>Privacy & Security</a>
          <a>Legal</a>

          <div class="vr mx-3 align-top mt-1"></div>

          <div class="d-inline-block text-decoration-underline">
            <a>Sweden</a>
            <a style="margin-left: 18px;">English</a>
          </div>
        </div>

        <span class="text-muted fs-small">
          <span>
            Copyright © Ethertia, Elytra. Partial rights reserved.
          </span>
          <small class="d-block mt-2">
            Except as otherwise noted, this site is not licensed under a Creative Commons Attribution 4.0 International License, and <br>
            code samples are not licensed under the 3-Clause BSD License.
          </small>
        </span>

      </div>
    </div>
  </footer>
</template>

<style scoped>

footer {
  background: #f2f2f2;
  padding: 0 64px;
}
.footer-linkmap > div {
  display: inline-block;
  vertical-align: top;
  margin-right: 90px;
}
.footer-linkmap > div > span:first-child {
  font-size: 14px;
  font-weight: bold;
  display: block;
}
.footer-linkmap a {
  display: block;
  color: #666!important;
  font-size: 14px;
  margin: 12px 0;
}
.fs-small {
  font-size: 12px;
}
.footer-right-decls > a {
  margin-left: 8px;
}
</style>

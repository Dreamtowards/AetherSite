<script setup lang="ts">
// defineProps<{
//
// }>()
</script>

<template>
  <header class="header-color-invert2">

    <div style="background: #dadada; line-height: 22px; font-size: 11px;">
      <div class="container top-nav">
        <a>Announcements</a>
        <a>Wiki</a>
        <a>Mods</a>
        <a>Maps</a>
        <a>Avatars</a>
        <a>Resourcepacks</a>
        <!--            <a>Texturepacks</a>-->
        <!--            <a>Shaderpacks</a>-->
        <a style="margin-right: 0;">Modpacks</a>
        <div class="vr align-middle" style="margin: 0 12px;"></div>
<!--        <a class="opacity-50 text-muted">|</a>-->
        <a>Servers</a>
        <a>Stats</a>

<!--        <div class="" style="">-->
<!--          <span>-->
<!--                    <span class="text-decoration-underline">Sweden</span>-->
<!--                                &nbsp;-->
<!--            <span class="text-decoration-underline">USD</span>-->
            &nbsp;
<!--            <span class="text-decoration-underline">EN</span>-->
<!--          </span>-->
<!--          &nbsp;&nbsp;-->
          <span class="float-end "  style="font-size: 110%;margin-left: 4px;opacity: 0.8">
            <a>Login</a>
            &nbsp;/&nbsp;
            <a>Register</a>
          </span>
<!--        </div>-->
      </div>
    </div>

    <div style="background: #e9e9e9;">
      <div class="main-nav container">
        <a class="main-nav-item d-inline-block">
          <!--                <img src="../res/elytra-fi-tint.png" height="27px">-->
          <!--                <img src="res/lp.png" height="36px" class="me-1">-->
          <!--                <img src="res/lpers.png" height="56px">-->
          <!--                <img src="res/tx.png" height="42px" class="me-1">-->
          <b>
            Ethertia
            · 以太效应
          </b>
        </a>

        <div class="dropdown">
          <a class="dropdown-toggle main-nav-item">Program</a>
<!--            <img src="@/assets/icon/expand.png" style="width: 7px;transform: rotate(90deg); margin-left: 4px;">-->

          <ul class="dropdown-menu">
            <li><span class="dropdown-hinter">Get Ethertia</span></li>
            <li><a class="dropdown-item" href="https://github.com/Dreamtowards/Ethertia/releases">Download Latest</a></li>
            <li><a class="dropdown-item" href="https://github.com/Dreamtowards/Ethertia/releasesbui">All Versions</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="https://github.com/users/Dreamtowards/projects/2">Roadmap</a></li>
            <li><a class="dropdown-item" href="#">Gallery</a></li>
            <li><a class="dropdown-item" href="#">Help</a></li>
            <li><a class="dropdown-item" href="#">FAQ</a></li>
          </ul>
        </div>

        <div class="dropdown">
          <a class="dropdown-toggle main-nav-item">Discussion</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Official News</a></li>
            <li><a class="dropdown-item" href="#">Development Discussion</a></li>
            <li><a class="dropdown-item" href="#">Gameplay Discussion</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><span class="dropdown-hinter">Et cetra</span></li>
            <li><a class="dropdown-item" href="#">Pocket Edition</a></li>
          </ul>
        </div>

        <div class="dropdown">
          <a class="dropdown-toggle main-nav-item">Extensions</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Mods</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><span class="dropdown-hinter">Resourcepacks</span></li>
            <li><a class="dropdown-item" href="#">Texturepacks</a></li>
            <li><a class="dropdown-item" href="#">Shaderpacks</a></li>
<!--            <li><a class="dropdown-item" href="#">Languages</a></li>-->
            <li><a class="dropdown-item" href="#">Sounds</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Maps</a></li>
            <li><a class="dropdown-item" href="#">Avatars</a></li>
            <li><a class="dropdown-item" href="#">Modpacks</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Servers</a></li>
          </ul>
        </div>

        <div class="dropdown">
          <a class="dropdown-toggle main-nav-item" data-bs-toggle="dropdown">Documentation</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Materials</a></li>
            <li><a class="dropdown-item" href="#">Items</a></li>
            <li><a class="dropdown-item" href="#">Biomes</a></li>
            <li><a class="dropdown-item" href="#">Recipes</a></li>
            <li><a class="dropdown-item" href="#">Commands</a></li>
            <li><a class="dropdown-item" href="#">Gamemodes</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><span class="dropdown-hinter">Development</span></li>
            <li><a class="dropdown-item" href="#">Getting Started to Dev</a></li>
            <li><a class="dropdown-item" href="#">Modding</a></li>
            <li><a class="dropdown-item" href="#">Resourcepack</a></li>
          </ul>
        </div>

        <div class="dropdown">
          <a class="dropdown-toggle main-nav-item">About</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="https://youtube.com/@dreamtowards">YouTube</a></li>
            <li><a class="dropdown-item" href="https://discord.gg/2gzHbuXF">Discord</a></li>
            <li><a class="dropdown-item" href="https://github.com/Dreamtowards/Ethertia">Github</a></li>
            <li><a class="dropdown-item" href="https://zh.wikipedia.org/wiki/Ethertia">Wikipedia</a></li>
            <li><a class="dropdown-item" href="https://jq.qq.com/?_wv=1027&k=tgM29oDM">QQ</a></li>
            <li><a class="dropdown-item" href="https://space.bilibili.com/19483166">Bilibili</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><span class="dropdown-hinter">Tools</span></li>
            <li><a class="dropdown-item" href="https://github.com/users/Dreamtowards/projects/2">Roadmap</a></li>
            <li><a class="dropdown-item" href="https://github.com/Dreamtowards/Ethertia/releases">All Versions</a></li>
            <li><a class="dropdown-item" href="#">Statistics</a></li>
            <li><a class="dropdown-item" href="#">Bug Tracker</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><span class="dropdown-hinter">Developers</span></li>
            <li><a class="dropdown-item" href="https://elytra.dev/~pris?bg=10">Eldrine Le Prismarine</a></li>
            <li><a class="dropdown-item" href="https://elytra.dev">Elytra Corporation</a></li>
            <li><a class="dropdown-item" href="#">...</a></li>
          </ul>
        </div>

        <div class="dropdown float-end" style="position: relative;">
          <a class="main-nav-item me-0">Profile</a>
          <ul class="dropdown-menu" style="position: absolute; right: 0;">
            <li><span class="dropdown-hinter">Signed in as</span></li>
            <li><a class="dropdown-item" href="#">Eldrine Le Prismarine</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Your profile</a></li>
            <li><a class="dropdown-item" href="#">Your avatars</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Help</a></li>
            <li><a class="dropdown-item" href="#">Settings</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Sign out</a></li>
          </ul>
        </div>

      </div>
    </div>

  </header>
</template>

<style scoped>
.dropdown-toggle::after {
  /*margin-bottom: -1px;*/
  border-top:   0.22em solid;
  border-right: 0.22em solid transparent;
  border-left:  0.22em solid transparent;
  border-bottom: 0;
}

.top-nav > a {
  margin-right: 13px;
  cursor: pointer;
}


.main-nav-item {
  margin-right: 20px;
  cursor: pointer;
  line-height: 56px;
  font-size: 17px;
  color: inherit;
  text-decoration: none;
  display: block;
}
.main-nav .dropdown:hover .dropdown-menu {
  display: block;
  margin-top: 0; /* remove the gap so it doesn't close */
}
.main-nav .dropdown {
  display: inline-block;
}
.main-nav .dropdown-menu {
  /*margin-top: 17px!important;*/
  border-radius: 0 0 5px 5px;
  border-top: none;
  backdrop-filter: blur(8px);
  background-color: #ffffff84;
  font-size: 15px;
  /*background: #e9e9e988;*/
  /*border: none;*/
  box-shadow: 0px 0px 8px 0px #00000015;
  padding: 6px 0;
}
.dropdown-item:focus {
  color: unset;
  background-color: unset;
}
.dropdown-item:hover {
  color: #fff;
  background-color: var(--bs-primary);
  cursor: default;
}
.dropdown-item {
  font-size: 14.4px;
  padding: 2px 12px;
  margin: 2px 8px;
  border-radius: 5px;
  width: unset;
  color: #111;
}
.dropdown-hinter {
  margin-left: 20px;
  margin-bottom: -2px;
  margin-top: 2px;
  font-size: 11px;
  opacity: 0.7;
  display: block;
}
.dropdown-divider {
  border: none;
  height: 2px;
  background-color: rgba(0,0,0,0.1);
}


</style>

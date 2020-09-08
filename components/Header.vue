<template>
  <div class="header">
    <div class="header-body">
      <div class="header-body-logo">
        <img
          class="header-body-logo-image"
          src="../assets/images/logo.svg"
          alt="logo"
        />
        <img
          class="header-body-logo-title"
          src="../assets/images/Pepelane.svg"
          alt="title"
        />
      </div>
      <h1 class="header-body-title">World's first affordable airsharing</h1>
      <div class="header-body-night_mode">
        <img
          class="header-body-night_mode-image"
          src="../assets/images/moon.svg"
          alt="moon"
        />
        <p class="header-body-night_mode-title">Night mode</p>
      </div>
      <div class="header-body-alarms">
        <img
          class="header-body-alarms-image-phrase"
          src="../assets/images/phrase.svg"
          alt="phrase"
        />
        <img
          class="header-body-alarms-image-notif"
          src="../assets/images/notif.svg"
          alt="notif"
        />
      </div>
      <div class="header-body-user">
        <p class="header-body-user-name">Bessie Cooper</p>
        <img
          class="header-body-user-avatar"
          src="../assets/images/avatar.svg"
          alt="avatar"
        />
      </div>
    </div>
  </div>
</template>
<style lang="scss">
@import '../assets/scss/header.scss';
</style>
<script>
export default {
  name: 'Header',
}
</script>

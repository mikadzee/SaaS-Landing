<template>
  <footer class="footer outer-container-padding border-top">
    <CommonLogo />

    <div class="footer-info">
      <ul class="text-average">
        <li><a href="#">© Wallet 2022</a></li>
        <li><a href="#">Privacy policy</a></li>
        <li><a href="#">Cookies policy</a></li>
        <li><a href="#">Terms of use</a></li>
      </ul>

      <div class="email-form text-body">
        <div class="input">
          <label class="text-body">Updates right to your Inbox</label>
          <input type="email" placeholder="Email Address">
        </div>
        <CommonButton class="button-secondary">Send</CommonButton>
      </div>
    </div>
  </footer>
</template>

<style scoped>
  @import "./footer.less";
</style>
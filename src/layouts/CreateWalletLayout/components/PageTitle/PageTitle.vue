<template>
  <div class="page-title">
    <div class="wrap">
      <div class="page-container">
        <div class="page-title">
          <h2>{{ $t("common.createWallet") }}</h2>
          <h5>{{ $t("createWallet.pageTitleAlreadyHave") }} <router-link to="/access-my-wallet">{{ $t("common.unlockWallet") }}</router-link></h5>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
@import 'PageTitle.scss';
</style>

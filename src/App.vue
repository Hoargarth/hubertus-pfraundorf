<template>
  <div class="main-container">
    <GlobalMenu/>
    <router-view/>
    <GlobalFooter/>
  </div>
</template>

<style lang="scss">
  @import '~@/assets/scss/abstract/_variables.scss';

  .page-content {
    max-width: $max-page-width;
    margin: 0 auto;
  }

  .main-container {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
</style>

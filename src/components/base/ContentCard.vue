<template>
  <div class="content-card">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'ContentCard',
  props: {
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import '~@/assets/scss/abstract/_variables.scss';

  .content-card {
    padding: $padding-sides;
    box-shadow: 0px 6px 13px 1px rgba(0,0,0,0.32);
  }
</style>

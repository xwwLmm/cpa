<template>
  <div :class="$style.container">123123
  </div>
</template>
<script>
  export default {}
</script>
<style lang="stylus" module>
  .container
    :global
      .iconfont
        display inline-block
        width 25px
        color $theme-color
</style>
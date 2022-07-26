<template>
  <h6 class="app-subtitle">
    <slot />
  </h6>
</template>

<script>

export default { name: 'AppSubtitle' };

</script>

<style lang="sass" scoped>

  .app-subtitle
    color: var(--primary-300)
    font-weight: 300
    font-size: 14px
    text-transform: none

    small
      font-size: .875em

</style>

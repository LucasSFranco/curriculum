<template>
  <h1 class="app-title">
    <template
      v-for="(letter, index) of title"
      :key="index"
    >
      <em v-if="letter === letter.toUpperCase()">{{ letter }}</em>
      <template v-else>
        {{ letter }}
      </template>
    </template>
    <slot />
  </h1>
</template>

<script>

export default {
  name: 'AppTitle',
  props: {
    title: { type: String, default: null },
  },
};

</script>

<style lang="sass" scoped>

  .app-title
    color: var(--primary-700)
    font-size: 24px
    font-weight: 600
    text-transform: uppercase

    em
      font-size: 32px
      font-style: normal
      font-weight: 500

</style>

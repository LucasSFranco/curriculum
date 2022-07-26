<template>
  <div class="app-card">
    <div class="shadow" />
    <a
      v-if="repository"
      :href="repository"
      target="_blank"
      class="icon"
    >
      <i class="fab fa-github" />
    </a>

    <div
      v-if="title"
      class="card-title"
    >
      <h3>
        <a
          v-if="href"
          :href="href"
          target="_blank"
        >
          {{ title }}
          <i class="fas fa-external-link-alt" />
        </a>
        <template v-else>
          {{ title }}
        </template>
      </h3>
      <small v-if="subtitle">{{ subtitle }}</small>
    </div>

    <slot />
  </div>
</template>

<script>
export default {
  name: 'AppCard',
  props: {
    title: { type: String, default: null },
    subtitle: { type: String, default: null },
    href: { type: String, default: null },
    repository: { type: String, default: null },
  },
};
</script>

<style lang="sass" scoped>

  .app-card
    position: relative

    background: var(--gray-700)

    &::after, &::before
      content: ''

      width: 0
      height: 0

      position: absolute

    &::before
      top: -2px
      left: -2px

      border-top: 12px solid var(--gray-900)
      border-right: 32px solid transparent

    &::after
      bottom: -2px
      right: -2px

      border-bottom: 12px solid var(--primary-900)
      border-left: 32px solid transparent

    .shadow
      width: 100%
      height: 100%

      position: absolute
      top: 8px
      left: 8px

      background: var(--primary-900)
      z-index: -1

      &::after
        content: ''

        position: absolute
        bottom: -2px
        right: -2px

        border-bottom: 12px solid var(--gray-900)
        border-left: 32px solid transparent

    .card-title
      background: var(--gray-800)
      padding: 8px 0
      text-align: center

      h3
        color: white
        font-size: 14px
        font-weight: 500
        text-transform: uppercase

        a
          color: inherit

          display: inline-flex
          justify-content: center
          gap: 8px

      small
        color: var(--gray-300)
        font-weight: 300
        font-size: 12px

    .icon
      position: absolute
      bottom: -8px
      right: -8px

      width: 64px
      height: 40px

      display: flex
      justify-content: center
      align-items: center

      background: var(--primary-900)
      z-index: 1

      i
        font-size: 24px
        color: white

      &::after, &::before
        content: ''

        position: absolute

      &::before
        top: -2px
        left: -2px

        border-top: 12px solid var(--gray-700)
        border-right: 32px solid transparent

      &::after
        bottom: -2px
        right: -2px

        border-bottom: 12px solid var(--gray-900)
        border-left: 32px solid transparent

</style>

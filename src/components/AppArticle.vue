<template>
  <article
    class="app-article"
    v-html="html"
  />
</template>

<script>

import MarkdownIt from 'markdown-it';
import MarkdownitSub from 'markdown-it-sub';
import MarkdownitSup from 'markdown-it-sup';

export default {
  name: 'AppArticle',
  props: {
    content: { type: String, default: '' },
  },
  computed: {
    html() {
      const md = new MarkdownIt()
        .use(MarkdownitSub)
        .use(MarkdownitSup);

      return md.render(this.content);
    },
  },

};
</script>

<style lang="sass">

  .app-article
    color: var(--gray-50)
    font-weight: 300
    padding: 16px
    line-height: 1.5em

    h1, h2, h3, h4
      color: white
      font-weight: 500
      margin-bottom: 4px
      text-transform: uppercase

    h1
      font-size: 1.125em

    h2
      font-size: 1em

    h3
      font-size: .875em

    h4
      font-size: .75em

    hr
      background-color: var(--gray-500)
      border: 0
      height: 1px
      margin: 16px 0

    code
      background: var(--primary-500)
      border-radius: 3px
      color: white
      font-size: .875em
      font-weight: 400
      padding: 0 4px
      white-space: nowrap

    strong
      font-weight: 500

    ul
      margin: 8px 0

      li
        color: var(--gray-50)
        font-size: .875em
        font-weight: 300
        text-indent: 8px

        &::before
          content: "•"
          position: absolute
          left: 8px
          color: var(--primary-500)

</style>

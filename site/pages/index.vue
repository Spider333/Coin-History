<template>
  <div class="container">
    <img src="/coin-story.svg">
    <vue-markdown :source="MarkdownSource" />
  </div>
</template>

<script>
import VueMarkdown from 'vue-markdown'
import MarkdownSource from '~/static/resources.md'
export default {
  components: {
    VueMarkdown
  },
  data () {
    return {
      MarkdownSource
    }
  }
}
</script>

<template>
  <div class="page">
    <section>
        <div class="container">
            <div class="title">
                <a href="http://coinstory.tech"><img src="~/assets/img-coin-story.png"></a>
                <div>Your shortcut to the crypto world</div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <vue-markdown :source="MarkdownSource" />
        </div>
    </section>
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

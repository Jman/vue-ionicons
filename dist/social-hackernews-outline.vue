<template>
  <div class="ion social-hackernews-outline-icon" name="social-hackernews-outline-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M416 96v320H96V96h320m32-32H64v384h384V64z"/><path d="M296.7 159H342l-63.9 120v72h-39.9v-72L172 159h47.1l39.7 83.6 37.9-83.6z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "social-hackernews-outline-icon",
    data () {
      let iconTitle = this.title ? this.title : "Social Hackernews Outline Icon"
      return {
        iconTitle
      }
    },
    props: {
      title: {
        type: String,
        default: ""
      }
    }
  }
</script>

<template>
  <div class="ion arrow-resize-icon" name="arrow-resize-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M288 96l49.9 49.9-63.9 63.8-128.1 128.2L96 288v128h128l-49.9-49.9 183.3-183.2 8.7-8.8L416 224V96z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "arrow-resize-icon",
    data () {
      let iconTitle = this.title ? this.title : "Arrow Resize Icon"
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

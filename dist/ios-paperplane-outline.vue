<template>
  <div class="ion ios-paperplane-outline-icon" name="ios-paperplane-outline-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M96 249.6l116.6 51.3L269.8 416 416 96 96 249.6zm132.1 46.9l155.7-166.2-114.6 248.9-41.1-82.7zm153.7-168.2l-165 157.1L134 249l247.8-120.7z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-paperplane-outline-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Paperplane Outline Icon"
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

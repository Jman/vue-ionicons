<template>
  <div class="ion ios-play-outline-icon" name="ios-play-outline-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M144 124.9L353.8 256 144 387.1V124.9M128 96v320l256-160L128 96z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-play-outline-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Play Outline Icon"
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

<template>
  <div class="ion ios-pause-icon" name="ios-pause-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M128 96h79v320h-79zM305 96h79v320h-79z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-pause-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Pause Icon"
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

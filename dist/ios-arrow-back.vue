<template>
  <div class="ion ios-arrow-back-icon" name="ios-arrow-back-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M352 128.4L319.7 96 160 256l159.7 160 32.3-32.4L224.7 256z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-arrow-back-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Arrow Back Icon"
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

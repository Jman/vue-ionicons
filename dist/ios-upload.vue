<template>
  <div class="ion ios-upload-icon" name="ios-upload-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M264 144v162h-16V144H96v304h320V144zM264 63.4l54.8 54.7 11.6-11.6L256 32l-74.5 74.5 11.7 11.6L248 63.4V144h16z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-upload-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Upload Icon"
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

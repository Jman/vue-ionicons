<template>
  <div class="ion ios-browsers-icon" name="ios-browsers-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M64 144v304h303.9V144H64z"/><path d="M144 64v64h240v240h64V64z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-browsers-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Browsers Icon"
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

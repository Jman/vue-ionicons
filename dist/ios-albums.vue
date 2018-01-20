<template>
  <div class="ion ios-albums-icon" name="ios-albums-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M480 128H32v320h448V128zM72 96h368v16H72zM104 64h304v16H104z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-albums-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Albums Icon"
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

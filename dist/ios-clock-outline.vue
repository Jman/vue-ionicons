<template>
  <div class="ion ios-clock-outline-icon" name="ios-clock-outline-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M256 48C141.1 48 48 141.1 48 256s93.1 208 208 208 208-93.1 208-208S370.9 48 256 48zm0 398.7c-105.1 0-190.7-85.5-190.7-190.7 0-105.1 85.5-190.7 190.7-190.7 105.1 0 190.7 85.5 190.7 190.7 0 105.1-85.6 190.7-190.7 190.7z"/><path d="M256 256h-96v17.3h113.3V128H256z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-clock-outline-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Clock Outline Icon"
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

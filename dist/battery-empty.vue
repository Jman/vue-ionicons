<template>
  <div class="ion battery-empty-icon" name="battery-empty-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M469.9 192H433v-54c0-5.5-4.3-10-9.9-10h-381c-5.6 0-10.1 4.5-10.1 10v236c0 5.5 4.5 10 10.1 10h381.1c5.5 0 9.9-4.5 9.9-10v-54H470c5.6 0 10.1-4.5 10.1-10V202c-.1-5.5-4.6-10-10.2-10zM448 288h-47v64H64V160h337v64h47v64z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "battery-empty-icon",
    data () {
      let iconTitle = this.title ? this.title : "Battery Empty Icon"
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

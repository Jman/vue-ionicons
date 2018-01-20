<template>
  <div class="ion android-arrow-dropright-icon" name="android-arrow-dropright-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M192 128l128 128-128 128z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-arrow-dropright-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Arrow Dropright Icon"
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

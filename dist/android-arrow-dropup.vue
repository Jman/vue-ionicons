<template>
  <div class="ion android-arrow-dropup-icon" name="android-arrow-dropup-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M128 320l128-128 128 128z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-arrow-dropup-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Arrow Dropup Icon"
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

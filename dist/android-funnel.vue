<template>
  <div class="ion android-funnel-icon" name="android-funnel-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M208 400h96v-47.994h-96V400zM32 112v47.994h448V112H32zm80 168.783h288v-49.555H112v49.555z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-funnel-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Funnel Icon"
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

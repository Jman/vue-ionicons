<template>
  <div class="ion minus-round-icon" name="minus-round-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M417.4 224H94.6C77.7 224 64 238.3 64 256s13.7 32 30.6 32h322.8c16.9 0 30.6-14.3 30.6-32s-13.7-32-30.6-32z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "minus-round-icon",
    data () {
      let iconTitle = this.title ? this.title : "Minus Round Icon"
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

<template>
  <div class="ion navigate-icon" name="navigate-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M480 32L32 224h256v256z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "navigate-icon",
    data () {
      let iconTitle = this.title ? this.title : "Navigate Icon"
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

<template>
  <div class="ion location-icon" name="location-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M256 64c-65.9 0-119.3 53.7-119.3 120 0 114.6 119.3 264 119.3 264s119.3-149.4 119.3-264c0-66.3-53.4-120-119.3-120zm0 178.2c-31.2 0-56.4-25.4-56.4-56.7 0-31.3 25.3-56.8 56.4-56.8 31.2 0 56.4 25.4 56.4 56.8 0 31.3-25.2 56.7-56.4 56.7z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "location-icon",
    data () {
      let iconTitle = this.title ? this.title : "Location Icon"
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

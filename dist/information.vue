<template>
  <div class="ion information-icon" name="information-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M288 448V192h-96v16h32v240h-32v16h128v-16zM255.8 144.5c26.6 0 48.2-21.6 48.2-48.2s-21.6-48.2-48.2-48.2-48.2 21.6-48.2 48.2 21.6 48.2 48.2 48.2z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "information-icon",
    data () {
      let iconTitle = this.title ? this.title : "Information Icon"
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

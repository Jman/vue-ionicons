<template>
  <div class="ion disc-icon" name="disc-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M256 158.9c-53.7 0-97.2 43.5-97.2 97.2s43.5 97.1 97.2 97.1 97.2-43.5 97.2-97.1c0-53.7-43.5-97.2-97.2-97.2zm0 140.6c-24 0-43.5-19.5-43.5-43.5s19.5-43.5 43.5-43.5 43.5 19.5 43.5 43.5-19.5 43.5-43.5 43.5z"/><path d="M256 32C132.3 32 32 132.3 32 256s100.3 224 224 224 224-100.3 224-224S379.7 32 256 32zm0 346.8c-67.8 0-122.8-55-122.8-122.8s55-122.8 122.8-122.8 122.8 55 122.8 122.8-55 122.8-122.8 122.8z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "disc-icon",
    data () {
      let iconTitle = this.title ? this.title : "Disc Icon"
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

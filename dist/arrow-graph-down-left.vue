<template>
  <div class="ion arrow-graph-down-left-icon" name="arrow-graph-down-left-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M32 384V224l60.8 60.8L223.7 144l107 112L480 128 330.7 330.7 223.7 224l-93.5 98.2L192 384z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "arrow-graph-down-left-icon",
    data () {
      let iconTitle = this.title ? this.title : "Arrow Graph Down Left Icon"
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

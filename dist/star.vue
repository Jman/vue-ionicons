<template>
  <div class="ion star-icon" name="star-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M480 200H308.519l-52.49-168-52.51 168H32l138.946 104.209L116 480l140-112 140 112-54.927-175.805z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "star-icon",
    data () {
      let iconTitle = this.title ? this.title : "Star Icon"
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

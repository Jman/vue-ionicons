<template>
  <div class="ion arrow-swap-icon" name="arrow-swap-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M64 328v48c0 4.4 3.6 8 8 8h248v64l128-96-128-96v64H72c-4.4 0-8 3.6-8 8zM448 184v-48c0-4.4-3.6-8-8-8H192V64L64 160l128 96v-64h248c4.4 0 8-3.6 8-8z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "arrow-swap-icon",
    data () {
      let iconTitle = this.title ? this.title : "Arrow Swap Icon"
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

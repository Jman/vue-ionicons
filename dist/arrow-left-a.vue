<template>
  <div class="ion arrow-left-a-icon" name="arrow-left-a-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M64.5 256.5l192 192v-112h192v-160h-192v-112z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "arrow-left-a-icon",
    data () {
      let iconTitle = this.title ? this.title : "Arrow Left A Icon"
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

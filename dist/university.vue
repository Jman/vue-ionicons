<template>
  <div class="ion university-icon" name="university-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M256 64L32 176.295l32 21.072V400l32 16V217.849L255.852 320l132.144-85.451L480 174.727z"/><path d="M390.13 256L256 343.768 120.531 256 112 337.529C128 349.984 224 416 256.002 448 288 416 384 350.031 400 337.561L390.13 256z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "university-icon",
    data () {
      let iconTitle = this.title ? this.title : "University Icon"
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

<template>
  <div class="ion android-star-icon" name="android-star-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M256 372.686L380.83 448l-33.021-142.066L458 210.409l-145.267-12.475L256 64l-56.743 133.934L54 210.409l110.192 95.525L131.161 448z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-star-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Star Icon"
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

<template>
  <div class="ion android-arrow-dropleft-circle-icon" name="android-arrow-dropleft-circle-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M464 256c0-114.875-93.125-208-208-208S48 141.125 48 256s93.125 208 208 208 208-93.125 208-208zm-272 0l96-96v192l-96-96z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-arrow-dropleft-circle-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Arrow Dropleft Circle Icon"
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

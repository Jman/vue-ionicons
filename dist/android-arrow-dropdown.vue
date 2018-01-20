<template>
  <div class="ion android-arrow-dropdown-icon" name="android-arrow-dropdown-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M128 192l128 128 128-128z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-arrow-dropdown-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Arrow Dropdown Icon"
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

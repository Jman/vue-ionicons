<template>
  <div class="ion android-radio-button-off-icon" name="android-radio-button-off-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M256 48C141.601 48 48 141.601 48 256s93.601 208 208 208 208-93.601 208-208S370.399 48 256 48zm0 374.399c-91.518 0-166.399-74.882-166.399-166.399S164.482 89.6 256 89.6 422.4 164.482 422.4 256 347.518 422.399 256 422.399z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-radio-button-off-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Radio Button Off Icon"
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

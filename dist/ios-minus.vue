<template>
  <div class="ion ios-minus-icon" name="ios-minus-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M256 48C141.1 48 48 141.1 48 256s93.1 208 208 208 208-93.1 208-208S370.9 48 256 48zm128 217H128v-17h256v17z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-minus-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Minus Icon"
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

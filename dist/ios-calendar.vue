<template>
  <div class="ion ios-calendar-icon" name="ios-calendar-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M64 192h384v256H64zM448 96h-96v48h-16V96H176v48h-16V96H64v80h384zM160 64h16v32h-16zM336 64h16v32h-16z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-calendar-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Calendar Icon"
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

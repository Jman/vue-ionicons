<template>
  <div class="ion ios-information-empty-icon" name="ios-information-empty-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><circle cx="251.5" cy="172" r="20"/><path d="M272 344V216h-48v8h16v120h-16v8h64v-8z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-information-empty-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Information Empty Icon"
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

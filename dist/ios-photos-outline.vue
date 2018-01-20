<template>
  <div class="ion ios-photos-outline-icon" name="ios-photos-outline-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M96 128v320h384V128H96zm368 304H112V144h352v288z"/><path d="M32 64v320h48v-16H48V80h352v32h16V64z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "ios-photos-outline-icon",
    data () {
      let iconTitle = this.title ? this.title : "Ios Photos Outline Icon"
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

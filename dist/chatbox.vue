<template>
  <div class="ion chatbox-icon" name="chatbox-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M124.3 400H277c14.4 0 14.4.1 21.3 5.2S384 464 384 464v-64h3.7c42.2 0 76.3-31.8 76.3-71.4V119.7c0-39.6-34.2-71.7-76.3-71.7H124.3C82.2 48 48 80.1 48 119.7v208.9c0 39.6 34.2 71.4 76.3 71.4z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "chatbox-icon",
    data () {
      let iconTitle = this.title ? this.title : "Chatbox Icon"
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

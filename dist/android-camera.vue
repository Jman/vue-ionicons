<template>
  <div class="ion android-camera-icon" name="android-camera-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><circle cx="256" cy="280" r="63"/><path d="M440 96h-88l-32-32H192l-32 32H72c-22.092 0-40 17.908-40 40v272c0 22.092 17.908 40 40 40h368c22.092 0 40-17.908 40-40V136c0-22.092-17.908-40-40-40zM256 392c-61.855 0-112-50.145-112-112s50.145-112 112-112 112 50.145 112 112-50.145 112-112 112z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "android-camera-icon",
    data () {
      let iconTitle = this.title ? this.title : "Android Camera Icon"
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

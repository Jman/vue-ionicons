<template>
  <div class="ion tshirt-icon" name="tshirt-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M480 96L320 48c-13.988 27.227-30.771 40.223-63.769 40.223C223.723 87.676 205.722 75 192 48L32 96l32 88 64-8-16 288h288l-16-288 64 8 32-88z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "tshirt-icon",
    data () {
      let iconTitle = this.title ? this.title : "Tshirt Icon"
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

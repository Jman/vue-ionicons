<template>
  <div class="ion medkit-icon" name="medkit-icon" :aria-labelledby="iconTitle">
    <svg width="1em" height="1em" viewBox="0 0 512 512"><path d="M472.2 144H352v-30.7C351 85.1 330.3 64 300.8 64h-89.6c-29.4 0-50.2 21.1-51.2 49.3V144H39.8c-4.4 0-7.8 3.6-7.8 8v288c0 4.4 3.3 8 7.8 8h432.5c4.4 0 7.8-3.6 7.8-8V152c-.1-4.4-3.4-8-7.9-8zM192 117.2v-1-1c0-9.7 8.6-19.3 18.8-19.3h90.4c10.1 0 18.8 9.5 18.8 19.3V144H192v-26.8zM352 320h-64v64h-64v-64h-64v-64h64v-64h64v64h64v64z"/></svg>
  </div>
</template>

<script>
  export default {
    name: "medkit-icon",
    data () {
      let iconTitle = this.title ? this.title : "Medkit Icon"
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

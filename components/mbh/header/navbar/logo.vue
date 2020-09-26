<template>
  <div>
    <template v-if="white">
      <div class="d-flex flex-row align-center">
        <img src="logo.png" style="width: 80px; height: 80px; margin-right: 18px">
        <div class="title" style="color: white">M.B.H UK <br>
          HOLDING LIMITED</div>
      </div>
    </template>
    <template v-else>
      <div class="d-flex flex-row align-center">
        <img src="logo.png" style="width: 80px; height: 80px; margin-right: 18px">
        <div style="color: #6D1F1C;" class="title">M.B.H UK <br>
          HOLDING LIMITED</div>
      </div>
    </template>
  </div>
</template>

<script>
export default {
  name: 'Logo',
  props: {
    white: {
      type: Boolean,
      default: false,
      required: false
    }
  }
}
</script>

<style scoped>
.title{
  font-family: Titillium Web;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 28px;
}
</style>

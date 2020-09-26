<template>
  <v-app>
    <nuxt />
  </v-app>
</template>

<script>
export default {
  head: {
    script: [
      { src: 'https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js', body: true },
    ]
  },
  data () {
    return {
      title: 'Vuetify.js'
    }
  },
}
</script>
<style>
html{
  font-family: Titillium Web;
  font-style: normal;
}
* {
  box-sizing: border-box;
}

a {
  text-decoration: none;
  color: white;
  font-size: 13px;
}

ul {
  padding: 0!important;
}

li {
  list-style: none;
}

input:focus, button:focus, select:focus {
  outline: none;
}

/** MBH **/
.mbh-container {
  padding: 0 64px;
}
@media screen and (max-width: 1159px) {
  .mbh-container {
    padding: 0 16px;
  }
}

</style>

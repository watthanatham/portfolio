<template>
  <v-container>
    <v-main :style="{backgroundColor: $vuetify.theme.dark ? '#0a0514': 'white'}">
      <Profile />
      <!-- <v-img :src="require('../assets/images/profile.jpg')"></v-img> -->
    </v-main>
  </v-container>
</template>
<script>
export default {
  data() {
  return {
    // profilePicture: require('../assets/images/profile.jpg')
  }
}
}
</script>
<style scoped>
</style>
<template>
  <div>
    <v-app-bar
      color="#FFFFFF"
      height="80"
      app
      :style="{ padding: $vuetify.breakpoint.mdAndUp ? '0px 100px' : '' }"
    >
      <v-toolbar-title
        @click="$router.push('/')"
        class="text-md-h5 font-weight-bold pointer"
      >
        WATT_DEV
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn text color="black" @click="$router.push('/')">Home</v-btn>

        <v-btn text color="black" @click="$router.push('/')"> About </v-btn>

        <v-btn text color="black" @click="$router.push('/')"> Contact </v-btn>
      </v-toolbar-items>
    </v-app-bar>
  </div>
</template>
<script>
export default {
  name: "Navbar",
};
</script>
<style scoped>
</style>
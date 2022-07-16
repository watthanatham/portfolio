<template>
  <v-footer app bottom fixed style="width: 100%" padless>
    <v-card
      tile
      flat
      class="pd-md-10 pa-5 text-center"
      style="width: 100%"
      color="surface"
    >
      <h2 class="text-md-h6 font-weight-bold">WATT.DEV</h2>
      <div class="text-center">
        <v-btn
          color="surface"
          class="mr-2"
          v-for="(b, i) in sm"
          :key="`sm${i}`"
          fab
          depressed
        >
          <v-icon v-on:click="select(b)">{{ b.icon }}</v-icon>
        </v-btn>
      </div>
    </v-card>
  </v-footer>
</template>
<script>
export default {
  data() {
    return {
      sm: [
        {
          icon: "mdi-facebook",
          link: "https://www.facebook.com/14KGallaxwat/",
        },
        {
          icon: "mdi-youtube",
          link: "https://www.youtube.com/channel/UCutL7kE1r3SdV2xBZHpVzKg",
        },
        {
          icon: "mdi-github",
          link: "#",
        },
        {
          icon: "mdi-gitlab",
          link: "https://gitlab.com/61160045",
        },
      ],
    };
  },
  methods: {
    select: function (web) {
      window.open(web.link, '_blank');
    },
  },
};
</script>
<style scoped>
.footer {
  bottom: 0;
  position: sticky;
  height: auto;
}
</style>
<template>
  <v-card height="70" class="mt-0">
    <v-footer dark absolute class="font-weight-normal">
      <v-col class="text-center" cols="12">
        &copy; {{ new Date().getFullYear() }}
        <v-btn class="ml-1" text icon color="pink">
          <v-img
            img
            contain
            max-height="40"
            src="@/assets/PSisotipo-lite.svg"
          ></v-img>
        </v-btn>
        <span class="ml-1 footer__username">by <strong>Biznet it</strong></span>
      </v-col>
    </v-footer>
  </v-card>
</template>

<script>
export default {}
</script>

<style scoped>
a:-webkit-any-link {
  text-decoration: none;
}
</style>

<template>
  <v-app id="inspire">
    <v-main class="white">
      <v-container>
        <v-row>
          <v-col>
            <v-sheet min-height="70vh" rounded="lg">
              <h1 v-if="error.statusCode === 404">
                {{ pageNotFound }}
              </h1>
              <h1 v-else>
                {{ otherError }}
              </h1>
              <NuxtLink class="underlinedLink" to="/"> Anasayfaya dön! </NuxtLink>
            </v-sheet>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  layout: 'empty',
  props: {
    error: {
      type: Object,
      default: null,
    },
  },
  data() {
    return {
      pageNotFound: 'Sayfa Bulunamadı!',
      otherError: 'An error occurred',
    }
  },
  head() {
    const title =
      this.error.statusCode === 404 ? this.pageNotFound : this.otherError
    return {
      title,
    }
  },
}
</script>

<style scoped>
h1 {
  font-size: 20px;
}
</style>

<template>
  <v-container>
    <v-row>
      <div
        class="col-lg-5 col-sm-5 col-xs-5 col"
        style="
          height: 100vh;
          display: grid;
          align-content: center;
          justify-content: center;
        "
      >
        <nuxt-link class="underlinedLink" to="/index2"
          >Proje Gelistirme</nuxt-link
        >
      </div>
      <div
        class="col-lg-2 col-sm-2 col-xs-2 col gm-logo-intro"
        style="
          height: 100vh;
          display: grid;
          align-content: center;
          justify-content: center;
        "
      >
        <div class="menuBarIntroLogo">
          <img src="~/assets/img/gunduz-medya-logo/GM-Black.png" />
        </div>
      </div>
      <div
        class="col-lg-5 col-sm-5 col-xs-5 col"
        style="
          height: 100vh;
          display: grid;
          align-content: center;
          justify-content: center;
        "
      >
        <nuxt-link class="underlinedLink" to="/web-projeler"
          >Icerik Uretimi</nuxt-link
        >
      </div>
    </v-row>
  </v-container>
</template>

<script>
export default {
  layout: 'mainPage',
}
</script>

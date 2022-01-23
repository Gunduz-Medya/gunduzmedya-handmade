<template>
  <v-footer dark padless>
    <v-card class="flex" flat tile>
      <v-card-title class="gm-red-background">
        <div class="container">
          <div class="row">
            <strong class="subheading">Bizi Takip Edin!</strong>

            <v-spacer></v-spacer>

            <v-btn v-for="icon in icons" :key="icon" class="mx-4" dark icon>
              <v-icon size="24px">
                {{ icon }}
              </v-icon>
            </v-btn>
          </div>
        </div>
      </v-card-title>

      <v-card-text class="py-2 white--text text-center">
        <div class="footer-container">
          <div class="container">
            <div class="row">
              <div class="col-lg-3 tal mt1">
                <img
                  class="menuBarLogo"
                  src="~/assets/img/gunduz-medya-logo/gunduz_medya-logos_transparent_small.png"
                />
                <p class="clg">
                  Dijital medyada yer almanın ne kadar önemli olduğunun farkında
                  olarak en yeni teknolojiler ile muhteşem markalar yaratıyoruz.
                </p>
              </div>
              <div class="col-lg-3">
                <ul>
                  <li>
                    <nuxt-link class="underlinedLink" to="/projelerimiz"
                      >Projelerimiz</nuxt-link
                    >
                  </li>
                  <li>
                    <nuxt-link class="underlinedLink" to="/video-produksiyon"
                      >Video Prodüksiyon</nuxt-link
                    >
                  </li>
                  <li>
                    <nuxt-link class="underlinedLink" to="/podcast"
                      >Podcast</nuxt-link
                    >
                  </li>
                  <li>
                    <nuxt-link class="underlinedLink" to="/canli-yayin"
                      >Canlı Yayın</nuxt-link
                    >
                  </li>
                </ul>
              </div>
              <div class="col-lg-3">
                <ul>
                  <li>
                    <nuxt-link class="underlinedLink" to="/hakkimizda"
                      >Hakkımızda</nuxt-link
                    >
                  </li>
                  <li>
                    <nuxt-link class="underlinedLink" to="/web-projeler"
                      >Web Projeler</nuxt-link
                    >
                  </li>
                  <li>
                    <nuxt-link class="underlinedLink" to="/mobil-uygulamalar"
                      >Mobil Uygulamalar</nuxt-link
                    >
                  </li>
                  <li>
                    <nuxt-link class="underlinedLink" to="/tasarim-calismalari"
                      >Tasarım Çalışmaları</nuxt-link
                    >
                  </li>
                </ul>
              </div>
              <div class="col-lg-3">
                <div class="addressCol">
                  <span>14 Wall Street</span>
                  <span>Manhattan, 10005, USA</span>
                  <span class="mobileNum">+90 (542) 187 88 17</span>
                </div>
              </div>
            </div>
          </div>
        </div>
        {{ new Date().getFullYear() }} — <strong>GM</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: ['mdi-facebook', 'mdi-twitter', 'mdi-linkedin', 'mdi-instagram'],
  }),
}
</script>

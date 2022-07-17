
<template>
  <v-container>
    <v-row>
      <v-col>
        <v-sheet class="gm_dflex" min-height="90vh" rounded="lg">
          <div class="gm_header col-lg-6">
            <div class="" style="display: flex; align-items: center">
              <div
                style="display: flex; flex-direction: column; max-width: 40rem"
              >
                <h3 class="header_title">
                  Dijital Medya <span class="subtitle">Proje Geliştirme</span>
                </h3>
                <p>
                  Dijital medyada yer almanın ne kadar önemli olduğunun farkında
                  olarak en yeni teknolojiler ile muhteşem markalar yaratıyoruz.
                  Her gün gelişerek geliştirmeye devam etmek en büyük
                  mutluluğumuz!
                </p>
                <nuxt-link class="gm-bordered-button" to="/hakkimizda"
                  ><span>Hakkımızda</span></nuxt-link
                >
              </div>
            </div>
          </div>
          <div class="headerImg col-lg-6">
            <img
              class="img-responsive"
              src="~/assets/img/project-development-mainpage/gm-proje-gelistirme.jpg"
            />
          </div>
        </v-sheet>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-sheet min-height="70vh" rounded="lg">
          <v-row>
            <v-col cols="12">
              <h4>Yazılım & Tasarım</h4>
            </v-col>
          </v-row>
          <v-row>
            <div class="col-lg-4">
              <h3>Yeni Teknoloji <span class="subtitle">Web Projeler</span></h3>
              <p>
                Birinci sınıf araçlar ve teknolojileri kullanarak, her cihazda
                iyi performans gösteren temiz ve ölçeklenebilir yapıda projeler
                üretiyoruz. Modern dil ve frameworkleri kullanmaya ve projenin
                özel ihtiyaçları için mevcut en iyi teknolojiyi seçmeye özen
                gösteriyoruz.
              </p>
              <nuxt-link class="underlinedLink" to="/web-projeler"
                >Web Projeler</nuxt-link
              >
            </div>
            <div class="col-lg-4">
              <h3>Android & iOS <span class="subtitle">Mobil Uygulamalar</span></h3>
              <p>
                Modern görünümlü arayüzlerin yanında, sürdürülebilir ve
                ölçeklenebilir kod tabanı ile tüm ekran boyutlarına uygun
                kullanışlı ve performanslı uygulamalar sağlayarak hem iOS hem de
                Android platformları için etkili mobil uygulamalar
                geliştiriyoruz.
              </p>
              <nuxt-link class="underlinedLink" to="/mobil-uygulamalar"
                >Mobil Uygulamalar</nuxt-link
              >
            </div>
            <div class="col-lg-4">
              <h3>Dijital Medya <span class="subtitle">Tasarım Çalışmaları</span></h3>
              <p>
                Tasarım, bir projeyi kullanıcıyla buluşturan en önemli
                unsurlardandır. Strateji ve deneyim, tasarımı üst seviyelere
                taşırken projeyi de daha anlaşılır ve kullanılır kılar. Ekrana
                baktığımızda gördüğümüz keyfi ve hazzı sizlerle de paylaşmak
                için can atıyoruz.
              </p>
              <nuxt-link class="underlinedLink" to="/tasarim-calismalari"
                >Tasarım Çalışmaları</nuxt-link
              >
            </div>
          </v-row>
        </v-sheet>
      </v-col>
    </v-row>
    <ProjectDevelopment />
    <v-row>
      <v-col>
        <v-sheet min-height="70vh" rounded="lg">
          <v-row>
            <v-col cols="12">
              <h4>Gündüz Medya</h4>
            </v-col>
          </v-row>
          <ContentFooter />
        </v-sheet>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  layout: 'default',
}
</script>

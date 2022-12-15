
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
                  Dijital Medya <span>Proje Geliştirme</span>
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
              <h4>İçerik Üretimi</h4>
            </v-col>
          </v-row>
          <v-row>
            <div class="col-lg-4">
              <h3>Video Prodüksiyon<span>Üretim ve Düzenleme</span></h3>
              <p>
                Dijitalleşen dünyada içerik üretiminin en önemli katmanı haline
                gelen video üretimi, çekim ve düzenleme konusunda trendleri
                takip eden ve yeni şeyler denemeyi asla bırakmayan ekibimiz ile
                birlikte paylaşımlara heyecan katıyoruz.
              </p>
              <nuxt-link class="underlinedLink" to="/video-produksiyon"
                >Video Prodüksiyon</nuxt-link
              >
            </div>
            <div class="col-lg-4">
              <h3>Podcast <span>Hikaye Anlatımı</span></h3>
              <p>
                Radyo ile büyümüş, o keyfi yaşamışlar olarak podcast'in tadını
                çıkaran, büyüsünü hisseden ve hissettirmeye çalışan bir yapıda
                podcast projelerimizi sizlerle paylaşıyoruz. Gündüz Medya
                yapımlarından en keyif aldığımız projelerden podcast serileri.
              </p>
              <nuxt-link class="underlinedLink" to="/podcast"
                >Podcast</nuxt-link
              >
            </div>
            <div class="col-lg-4">
              <h3>Canlı Yayın <span>İçerikler</span></h3>
              <p>
                Popüler içerik üretim kanallarından olan canlı yayın
                platformlarında farklı kategorilerde içerikler üretiyoruz. Canlı
                yayın altyapısı için projelendirme desteğimizi yayın tasarımı,
                telifsiz müzik üretimi ve kurulum gibi konulardaki iş
                birliklerimiz ile güçlendiriyoruz.
              </p>
              <nuxt-link class="underlinedLink" to="/canli-yayin"
                >Canlı Yayın</nuxt-link
              >
            </div>
          </v-row>
        </v-sheet>
      </v-col>
    </v-row>
    <ProjectContentCreation />
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

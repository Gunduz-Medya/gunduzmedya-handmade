<template>
  <v-container>
    <v-row>
      <v-col>
        <v-sheet min-height="90vh" rounded="lg">
          <div class="gm_header">
            <div class="" style="display: flex; align-items: center">
              <div
                style="display: flex; flex-direction: column; max-width: 40rem"
              >
                <h3 class="header_title">
                  Gündüz Medya <span>Geliştirme & Yönetim</span>
                </h3>
                <p>
                  Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                  Dolores vitae, ad eum adipisci consectetur possimus
                  repudiandae, nostrum dolorem earum ex inventore vel facilis
                  similique officia sunt, est veniam quaerat. Molestias?
                </p>
              </div>
            </div>
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
              <h3>Yeni Teknoloji <span>Web Projeler</span></h3>
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
              <h3>Android & iOS <span>Mobil Uygulamalar</span></h3>
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
              <h3>Dijital Medya <span>Tasarım Çalışmaları</span></h3>
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
    <v-row>
      <v-col>
        <img
          class="img-responsive"
          src="~/assets/img/gunduz-medya-wallpaper.jpg"
        />
      </v-col>
    </v-row>
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
  data: () => ({}),
}
</script>
<style></style>

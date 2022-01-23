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
              src="https://www.atolye15.com/img/jumbotron/expertise-ui-ux-design.jpg"
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
        <v-sheet min-height="70vh" rounded="lg">
          <v-row>
            <v-col cols="12">
              <h4>Projelerimiz</h4>
            </v-col>
          </v-row>
          <div class="gm-projects">
            <div class="gm-projects__item">
              <img
                class="gm-projects__img"
                alt=""
                src="~/assets/img/projects/bg.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img"
                alt=""
                src="~/assets/img/projects/vaktindeye.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img"
                alt=""
                src="~/assets/img/projects/kodburada.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img"
                alt=""
                src="~/assets/img/projects/devstup.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img lazyloaded"
                data-srcset="https://www.atolye15.com/img/clients/mercedesbenz.png 1x, img/clients/mercedesbenz@2x.png 2x"
                data-src="https://www.atolye15.com/img/clients/mercedesbenz.png"
                alt="Mercedes-Benz"
                srcset="
                  https://www.atolye15.com/img/clients/mercedesbenz.png 1x,
                  img/clients/mercedesbenz@2x.png                       2x
                "
                src="https://www.atolye15.com/img/clients/mercedesbenz.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img lazyloaded"
                data-srcset="https://www.atolye15.com/img/clients/mercedesbenz.png 1x, img/clients/mercedesbenz@2x.png 2x"
                data-src="https://www.atolye15.com/img/clients/mercedesbenz.png"
                alt="Mercedes-Benz"
                srcset="
                  https://www.atolye15.com/img/clients/mercedesbenz.png 1x,
                  img/clients/mercedesbenz@2x.png                       2x
                "
                src="https://www.atolye15.com/img/clients/mercedesbenz.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img lazyloaded"
                data-srcset="https://www.atolye15.com/img/clients/mercedesbenz.png 1x, img/clients/mercedesbenz@2x.png 2x"
                data-src="https://www.atolye15.com/img/clients/mercedesbenz.png"
                alt="Mercedes-Benz"
                srcset="
                  https://www.atolye15.com/img/clients/mercedesbenz.png 1x,
                  img/clients/mercedesbenz@2x.png                       2x
                "
                src="https://www.atolye15.com/img/clients/mercedesbenz.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img lazyloaded"
                data-srcset="https://www.atolye15.com/img/clients/mercedesbenz.png 1x, img/clients/mercedesbenz@2x.png 2x"
                data-src="https://www.atolye15.com/img/clients/mercedesbenz.png"
                alt="Mercedes-Benz"
                srcset="
                  https://www.atolye15.com/img/clients/mercedesbenz.png 1x,
                  img/clients/mercedesbenz@2x.png                       2x
                "
                src="https://www.atolye15.com/img/clients/mercedesbenz.png"
              />
            </div>
            <div class="gm-projects__item">
              <img
                class="gm-projects__img lazyloaded"
                data-srcset="https://www.atolye15.com/img/clients/mercedesbenz.png 1x, img/clients/mercedesbenz@2x.png 2x"
                data-src="https://www.atolye15.com/img/clients/mercedesbenz.png"
                alt="Mercedes-Benz"
                srcset="
                  https://www.atolye15.com/img/clients/mercedesbenz.png 1x,
                  img/clients/mercedesbenz@2x.png                       2x
                "
                src="https://www.atolye15.com/img/clients/mercedesbenz.png"
              />
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
              <h4>Gündüz Medya</h4>
            </v-col>
          </v-row>
          <v-row>
            <v-col md="12" sm="12" lg="6">
              <h3 class="gm-color-red">Biz Kimiz?</h3>
              <p class="pb40">
                Daima üreten, gelişen, geliştiren ve asla yerinde saymamak için
                sürekli çok çalışan bir ekibiz. Tüm projelerimizde, işin
                başından sonuna dek içimize sinene kadar titizlikle hareket
                ediyoruz. Yazılım, tasarım, reklam ve içerik üretiminde
                edindiğimiz tüm tecrübeleri yarını anlamakta ve öğrenmekte
                kullanıyoruz.
              </p>
              <nuxt-link class="gm-bordered-button" to="/hakkimizda"
                ><span>Hakkımızda</span></nuxt-link
              >
            </v-col>
            <v-col md="12" sm="12" lg="6">
              <h3 class="gm-color-red">Neler Yapıyoruz?</h3>
              <p class="pb40">
                Yazıyoruz, çiziyoruz, çekim yapıyoruz, üretiyoruz ve en önemlisi
                eğlenerek öğreniyoruz. Yeni teknolojiler kullanmamız sayesinde
                biz de gelişiyoruz ve yeni çağa her zaman ayak uydurmaya devam
                ediyoruz. Dijital medyada projeler geliştiriyoruz ve bu projeler
                için gerekli olan teknolojileri çantamıza eklemeye devam
                ediyoruz.
              </p>
              <nuxt-link class="gm-bordered-button" to="/hizmetlerimiz"
                ><span>Hizmetlerimiz</span></nuxt-link
              >
            </v-col>
          </v-row>
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

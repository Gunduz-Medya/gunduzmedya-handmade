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
                  Gündüz Medya <span>Geliştirme & Yönetim</span>
                </h3>
                <p>
                  YAZI DEĞİŞECEK:Daima üreten, gelişen, geliştiren ve asla yerinde saymamak
                  için sürekli çok çalışan bir ekibiz. Tüm projelerimizde, işin
                  başından sonuna dek içimize sinene kadar titizlikle hareket
                  ediyoruz. Yazılım, tasarım, reklam ve içerik üretiminde
                  edindiğimiz tüm tecrübeleri yarını anlamakta ve öğrenmekte
                  kullanıyoruz.
                </p>
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
        <img
          class="img-responsive"
          src="~/assets/img/gunduz-medya-wallpaper.jpg"
        />
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-sheet min-height="60vh" rounded="lg">
          <v-row>
            <v-col cols="12">
              <h4>Gündüz Medya</h4>
            </v-col>
          </v-row>
          <v-row>
            <div class="col-lg-6 bigBoldText">
              Daima üreten, gelişen, geliştiren ve asla yerinde saymamak için
              sürekli çok çalışan bir ekibiz. Tüm projelerimizde, işin başından
              sonuna dek içimize sinene kadar titizlikle hareket ediyoruz.
              Yazılım, tasarım, reklam ve içerik üretiminde edindiğimiz tüm
              tecrübeleri yarını anlamakta ve öğrenmekte kullanıyoruz.
            </div>
            <div class="col-lg-6">
              Yazıyoruz, çiziyoruz, çekim yapıyoruz, üretiyoruz ve en önemlisi
              eğlenerek öğreniyoruz. Yeni teknolojiler kullanmamız sayesinde biz
              de gelişiyoruz ve yeni çağa her zaman ayak uydurmaya devam
              ediyoruz. Dijital medyada projeler geliştiriyoruz ve bu projeler
              için gerekli olan teknolojileri çantamıza eklemeye devam ediyoruz.
              Birinci sınıf araçları ve teknolojileri kullanarak, her cihazda
              iyi performans gösteren temiz ve anlaşılır kodlar yazıyoruz.
              Ürünlerimizin ve projelerimizin kullanıcılara en doğru hizmeti
              vermesinin öncesinde geliştiren bizlerin kodları hem rahat
              anlayabilmesi hem de rahat etmesi önem verdiğimiz konulardandır.
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
              <h4>Gündüz Medya</h4>
            </v-col>
          </v-row>
          <v-row>
            <v-col md="12" sm="12" lg="6">
              <h3 class="gm-color-red">Biz Kimiz?</h3>
              <p class="pb40">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque
                nulla quibusdam impedit a pariatur, cum aperiam molestias sequi!
                Quae voluptas rerum magnam officiis non eaque quidem aut!
                Adipisci, repellendus. Asperiores!
              </p>
              <nuxt-link class="gm-bordered-button" to="/hakkimizda"
                ><span>Hakkımızda</span></nuxt-link
              >
            </v-col>
            <v-col md="12" sm="12" lg="6">
              <h3 class="gm-color-red">Neler Yapıyoruz?</h3>
              <p class="pb40">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque
                nulla quibusdam impedit a pariatur, cum aperiam molestias sequi!
                Quae voluptas rerum magnam officiis non eaque quidem aut!
                Adipisci, repellendus. Asperiores!
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
<style>
.c-blockquote {
  margin: 0;
}
.c-blockquote__content {
  margin-bottom: 0;
  color: #424242;
  font-size: 2rem;
  line-height: 1.3333333333;
}
.u-color-primary {
  color: #fe2d5b;
  display: inline;
}
</style>

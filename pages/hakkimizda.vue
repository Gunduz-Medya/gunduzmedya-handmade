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
                  YAZI DEĞİŞECEK:Daima üreten, gelişen, geliştiren ve asla
                  yerinde saymamak için sürekli çok çalışan bir ekibiz. Tüm
                  projelerimizde, işin başından sonuna dek içimize sinene kadar
                  titizlikle hareket ediyoruz. Yazılım, tasarım, reklam ve
                  içerik üretiminde edindiğimiz tüm tecrübeleri yarını anlamakta
                  ve öğrenmekte kullanıyoruz.
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
              <h4>Takımımız</h4>
            </v-col>
          </v-row>
          <v-row>
            <div class="gm-team">
              <div
                v-for="(x, index) in 5"
                :key="index"
                class="col-lg-3 col-md-3 col-sm-3 gm-team-card"
              >
                <img
                  class="gm-team-card-img"
                  src="https://pbs.twimg.com/profile_images/1081208546128289792/GjPT_D33_400x400.jpg"
                  alt=""
                />
                <!-- <hr> -->
                <h5>Barış Gündüz</h5>
                <p>CEO, Founder</p>
              </div>
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

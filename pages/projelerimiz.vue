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
</style>

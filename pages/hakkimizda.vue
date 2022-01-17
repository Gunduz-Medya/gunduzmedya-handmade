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
        <v-sheet min-height="30vh" rounded="lg">
          <blockquote class="c-blockquote">
            <p class="c-blockquote__content c-blockquote__content--medium">
              We are partners with more than
              <span class="u-color-primary">150</span> great clients from
              <span class="u-color-primary">8</span> different countries around
              the globe to create more than
              <span class="u-color-primary">200</span> amazing products with our
              <span class="u-color-primary">28</span> passionate team members.
            </p>
          </blockquote>
        </v-sheet>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <img class="img-responsive" src="~/assets/img/gunduz-medya-wallpaper.jpg" />
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

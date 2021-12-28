<template>
  <v-app id="inspire">
    <MenuBar />
    <v-main class="white">
      <v-container>
        <v-row>
          <v-col>
            <v-sheet min-height="70vh" rounded="lg">
              <v-carousel v-model="model">
                <v-carousel-item v-for="(color, i) in colors" :key="color">
                  <v-sheet :color="color" height="100%" tile>
                    <v-row class="fill-height" align="center" justify="center">
                      <div class="text-h2">Slide {{ i + 1 }}</div>
                    </v-row>
                  </v-sheet>
                </v-carousel-item>
              </v-carousel>
            </v-sheet>
          </v-col>
        </v-row>
        <v-row>
          <v-col>
            <v-sheet min-height="70vh" rounded="lg">
              <!-- <h1>Gündüz Medya</h1>
              <v-divider style="padding-bottom: 40px"></v-divider> -->
              <v-row>
                <v-col cols="4">
                  <h3>Dijital medya <span>Video İçerikleri</span></h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Atque nulla quibusdam impedit a pariatur, cum aperiam
                    molestias sequi! Quae voluptas rerum magnam officiis non
                    eaque quidem aut! Adipisci, repellendus. Asperiores!
                  </p>
                </v-col>
                <v-col cols="4">
                  <h3>Dijital medya</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Atque nulla quibusdam impedit a pariatur, cum aperiam
                    molestias sequi! Quae voluptas rerum magnam officiis non
                    eaque quidem aut! Adipisci, repellendus. Asperiores!
                  </p>
                </v-col>
                <v-col cols="4">
                  <h3>Dijital medya</h3>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Atque nulla quibusdam impedit a pariatur, cum aperiam
                    molestias sequi! Quae voluptas rerum magnam officiis non
                    eaque quidem aut! Adipisci, repellendus. Asperiores!
                  </p>
                </v-col>
              </v-row>
            </v-sheet>
          </v-col>
        </v-row>
      </v-container>
      <Footer />
    </v-main>
  </v-app>
</template>

<script>
export default {
  data: () => ({
    links: ['Hakkımızda', 'Projelerimiz', 'Hizmetlerimiz', 'İletişim'],
    model: 0,
    colors: ['primary', 'secondary', 'yellow darken-2', 'red', 'orange'],
  }),
}
</script>
<style>
h3 {
    font-size: 2.3333333333em;
    letter-spacing: -1px;
    margin-bottom: 1.75rem;
    color: #454545;
}
span {
    display: block;
    color: #fe2d5b;
}
</style>

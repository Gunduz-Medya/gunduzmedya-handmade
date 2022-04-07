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
                  Android & iOS <span>Mobil Uygulamalar</span>
                </h3>
                <p>
                  Modern görünümlü arayüzlerin yanında, sürdürülebilir ve
                  ölçeklenebilir kod tabanı ile tüm ekran boyutlarına uygun
                  kullanışlı ve performanslı uygulamalar sağlayarak hem iOS hem
                  de Android platformları için etkili mobil uygulamalar
                  geliştiriyoruz.
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
              <h4>Web Projeler</h4>
            </v-col>
          </v-row>
          <v-row>
            <div class="col-lg-6">
              <h3>Evrensel <span>Uygulama Geliştirme</span></h3>
              <p>
                Mobil geliştiricilerimiz hem yerel platformlarda hem de
                JavaScript'te deneyim sahibidir. React-Native sayesinde iOS ve
                Andorid için bakımı kolay ve anlaşılması kolay kod tabanları
                oluşturuyoruz.
              </p>
            </div>
            <div class="col-lg-6">
              <h3>Takip <span> Pazarlama</span></h3>
              <p>
                Kullanıcı eylemlerini nasıl izleyeceğinizi biliyoruz ve bu
                eylemlerden kararlar almanıza izin veriyoruz. Firebase, Mixpanel
                vb. ile olan deneyimimiz, her kullanıcıyı takip edebilecek ve
                onlarla kolayca etkileşime geçebileceksiniz.
              </p>
            </div>
            <div class="col-lg-6">
              <h3>Gerçek Zamanlı Veri <span> Mesajlaşma</span></h3>
              <p>
                Gerçek zamanlı veri akışları ve mesajlaşma konusundaki
                uzmanlığımız sayesinde, kullanıcılarınız herhangi bir bildirimi
                zamanında alacak ve uygulamanızın sohbete ihtiyacı varsa,
                diğerleriyle gerçek zamanlı olarak sorunsuz bir şekilde
                etkileşime geçecektir.
              </p>
            </div>
            <div class="col-lg-6">
              <h3>Otomatize Edilmiş<span> Geliştirme</span></h3>
              <p>
                "Bir şey otomatikleştirilebiliyorsa, onu otomatik hale getir"
                demeyi seviyoruz. Geliştirici ekibimiz, insan hatasını mümkün
                olduğunca az yapmak için ilk taahhütten beta sürümüne kadar her
                şeyi otomatik hale getirir.
              </p>
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
              <h4>Araçlar ve Teknolojiler</h4>
            </v-col>
          </v-row>
          <v-row>
            <div class="col-lg-3 gm_dflex">
              <img
                class="img-13"
                src="~/assets/img/tech-stack/firebase.svg"
                alt=""
              />
              <span class="tech-stack-text">Firebase</span>
            </div>
            <div class="col-lg-3 gm_dflex">
              <img
                class="img-13"
                src="~/assets/img/tech-stack/react-native.svg"
                alt=""
              />
              <span class="tech-stack-text">React Native</span>
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
<style></style>

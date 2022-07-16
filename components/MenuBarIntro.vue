<template>
  <v-app-bar
    app
    color="white"
    class="menuBarIntro"
    style="display: grid; align-items: center; justify-content: center"
  >
    <v-container class="py-0 fill-height">
      <div>
        <img
          class="menuBarIntroLogo"
          src="~/assets/img/gunduz-medya-logo/GM-Black.png"
        />
      </div>
    </v-container>
  </v-app-bar>
</template>
<script>
export default {
  data() {
    return {
      menu: {
        home: '/',
        about: '/hakkimizda',
        projects: '/projelerimiz',
        expertise: '/hizmetlerimiz',
        contact: '/iletisim',
      },
    }
  },
}
</script>
<style lang="sass">
.v-application a
  color: #5c5c5c
  text-decoration: none
  padding: 0px 5px 0px 5px
</style>

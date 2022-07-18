<template>
  <v-app-bar app color="white" class="menuBar">
    <v-container class="py-0 fill-height gm-centered-content">
      <div>
        <NuxtLink class="menuBarLink" to="/">
          <img
            class="menuBarLogo"
            src="~/assets/img/gunduz-medya-logo/GM-Black.png"
          />
        </NuxtLink>
      </div>

       <v-responsive>
        <NuxtLink class="menuBarLink" :to="menu.home">Anasayfa</NuxtLink>
        <NuxtLink class="menuBarLink" :to="menu.about">Hakkımızda</NuxtLink>
        <NuxtLink class="menuBarLink" :to="menu.projects"
          >Projelerimiz</NuxtLink
        >
        <NuxtLink class="menuBarLink" :to="menu.expertise"
          >Hizmetlerimiz</NuxtLink
        >
        <NuxtLink class="menuBarLink" :to="menu.contact">İletişim</NuxtLink>
      </v-responsive>
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

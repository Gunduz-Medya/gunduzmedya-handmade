<template>
  <v-app-bar app color="white" flat>
      <v-container class="py-0 fill-height">
        <div>GündüzMEDYA</div>

        <v-spacer></v-spacer>

        <v-responsive>
           <NuxtLink class="menuBarLink" :to="menu.home">Anasayfa</NuxtLink>
           <NuxtLink class="menuBarLink" :to="menu.about">Hakkımızda</NuxtLink>
           <NuxtLink class="menuBarLink" :to="menu.projects">Projelerimiz</NuxtLink>
           <NuxtLink class="menuBarLink" :to="menu.expertise">Hizmetlerimiz</NuxtLink>
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
        contact: '/iletisim'
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

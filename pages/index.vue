<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          Bem vindo ao meu portfólio
        </v-card-title>
        <v-card-text>
          <p>Essa aplicação possui o objetivo de explorar os elemetos de uma aplicação Server-side redering propostas no exercício 2 da disciplina de Arquitetura de Front-Ends.</p>
          <p>Foi utilizada a biblioteca de Vuetify UI com o Nuxt.js</p>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>

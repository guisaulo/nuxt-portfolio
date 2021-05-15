<template>
  <v-card class="mx-auto">
    <AboutCardGuilherme/>
    <SkillsCardGuilherme/>
    <ExperienceCardGuilherme/>
    <EducationCardGuilherme/>
  </v-card>
</template>

<script>
import AboutCardGuilherme from '../components/cards/AboutCardGuilherme.vue'
import SkillsCardGuilherme from '../components/cards/SkillsCardGuilherme.vue'
import ExperienceCardGuilherme from '../components/cards/ExperienceCardGuilherme.vue'
import EducationCardGuilherme from '../components/cards/EducationCardGuilherme.vue'

export default {
  name: 'Guilherme',
  components: { AboutCardGuilherme, SkillsCardGuilherme, ExperienceCardGuilherme, EducationCardGuilherme }
}
</script>
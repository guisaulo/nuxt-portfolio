<template>
  <v-card class="mx-auto">
    <AboutCardJoao/>
    <SkillsCardJoao/>
    <ExperienceCardJoao/>
    <EducationCardJoao/>    
  </v-card>
</template>

<script>
import AboutCardJoao from '../components/cards/AboutCardJoao.vue'
import SkillsCardJoao from '../components/cards/SkillsCardJoao.vue'
import ExperienceCardJoao from '../components/cards/ExperienceCardJoao.vue'
import EducationCardJoao from '../components/cards/EducationCardJoao.vue'

export default {
  name: 'JoaoBrasil',
  components: { AboutCardJoao, SkillsCardJoao, ExperienceCardJoao, EducationCardJoao }
}
</script>
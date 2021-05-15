<template>
  <v-card class="mx-auto">
    <AboutCard/>
    <SkillsCard/>
    <ExperienceCard/>
    <EducationCard/>
  </v-card>
</template>

<script>
import AboutCard from '../components/guilherme/AboutCard.vue'
import EducationCard from '../components/guilherme/EducationCard.vue'
import ExperienceCard from '../components/guilherme/ExperienceCard.vue'
import SkillsCard from '../components/guilherme/SkillsCard.vue'

export default {
  name: 'Guilherme',
  components: { AboutCard, EducationCard, ExperienceCard, SkillsCard }
}
</script>
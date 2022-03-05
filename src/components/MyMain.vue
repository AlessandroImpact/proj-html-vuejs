<template>
<section>
    <JumbotronTop/>
    <MissionSection/>
    <FeatureSection/>
    <AskAnExpert/>
    
</section>
  
</template>

<script>
import AskAnExpert from './partial/AskAnExpert.vue'
import JumbotronTop from './partial/JumbotronTop.vue'
import FeatureSection from './partial/FeatureSection.vue'
import MissionSection from './partial/MissionSection.vue'

export default {
    name:'MyMain',
    components: {
        AskAnExpert,
        JumbotronTop,
        FeatureSection,
        MissionSection
    }

}
</script>

<style>

</style>
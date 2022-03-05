<template>
<section>
    <JumbotronTop/>
    <MissionSection/>
    <FeatureSection/>
    <AskAnExpert/>
    <EnvatoSection/>
    
</section>
  
</template>

<script>
import AskAnExpert from './partial/AskAnExpert.vue'
import JumbotronTop from './partial/JumbotronTop.vue'
import FeatureSection from './partial/FeatureSection.vue'
import MissionSection from './partial/MissionSection.vue'
import EnvatoSection from './partial/EnvatoSection.vue'

export default {
    name:'MyMain',
    components: {
        AskAnExpert,
        JumbotronTop,
        FeatureSection,
        MissionSection,
        EnvatoSection
    }

}
</script>

<style>

</style>
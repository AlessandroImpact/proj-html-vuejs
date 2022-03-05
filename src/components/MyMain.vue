<template>
<section>
    <JumbotronTop/>
    <MissionSection/>
    <FeatureSection/>
    <AskAnExpert/>
    <EnvatoSection/>
    <QualityCardSection/>
    <WorkTogether/>
    
</section>
  
</template>

<script>
import AskAnExpert from './partial/AskAnExpert.vue'
import JumbotronTop from './partial/JumbotronTop.vue'
import FeatureSection from './partial/FeatureSection.vue'
import MissionSection from './partial/MissionSection.vue'
import EnvatoSection from './partial/EnvatoSection.vue'
import WorkTogether from './partial/WorkTogether.vue'
import QualityCardSection from './partial/QualityCardSection.vue'

export default {
    name:'MyMain',
    components: {
        AskAnExpert,
        JumbotronTop,
        FeatureSection,
        MissionSection,
        EnvatoSection,
        QualityCardSection,
        WorkTogether
    }

}
</script>

<style>

</style>
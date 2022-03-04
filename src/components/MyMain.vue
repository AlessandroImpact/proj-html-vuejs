<template>
<section>
    <JumbotronTop/>
    <FeatureSection/>
    <AskAnExpert/>
</section>
  
</template>

<script>
import AskAnExpert from './partial/AskAnExpert.vue'
import JumbotronTop from './partial/JumbotronTop.vue'
import FeatureSection from './partial/FeatureSection.vue'

export default {
    name:'MyMain',
    components: {
        AskAnExpert,
        JumbotronTop,
        FeatureSection
    }

}
</script>

<style>

</style>
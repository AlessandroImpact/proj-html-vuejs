<template>
<section>
    <JumbotronTop/>
    <AskAnExpert/>
</section>
  
</template>

<script>
import AskAnExpert from './partial/AskAnExpert.vue'
import JumbotronTop from './partial/JumbotronTop.vue'

export default {
    name:'MyMain',
    components: {
        AskAnExpert,
        JumbotronTop
    }

}
</script>

<style>

</style>
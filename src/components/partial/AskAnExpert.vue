<template>
  
  <section class="d-flex justify-content-around align-items-center text-white">

      <div>
          <h4 class="text-uppercase">Question about a judical issue? Ask our experts. </h4>
      </div>

    <div>

        <a class="btn text-uppercase text-white rounded color-btn-ask" href="http://">Ask an Expert</a>

    </div>

  </section>

</template>

<script>
export default {
    name: 'AskAnExpert',
    

}
</script>

<style lang="scss" scoped>
@import './style/general.scss';

section {
    background-color: $askcolor;
    min-height: 150px;

}

.color-btn-ask {
    background-color: $ask2color;
}



</style>


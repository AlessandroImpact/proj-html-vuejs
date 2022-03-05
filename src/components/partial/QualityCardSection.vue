<template>
  <section class="  mybg">

      <div class="  d-flex justify-content-center align-items-center   py-5 mybg">

      <div class="feature-card  text-center myborder bg-white">
           <img src="./images/law_7.jpg" alt="" class="my-4">
          <h5 class="text-uppercase ">international</h5>
          <p class="mx-4">Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn font-weight-bold mb-4">LEARN MORE</button>
    

      </div>

      <div class="feature-card  text-center myborder bg-white">
           <img src="./images/law_8.jpg" alt="" class="my-4">
          <h5  class="text-uppercase font-weight-bold">partnerships</h5>
          <p class="mx-4">Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn font-weight-bold mb-4">LEARN MORE</button>
           
          
      </div>

      <div class="feature-card  text-center myborder bg-white">
           <img src="./images/law_3.jpg" alt="" class="my-4">
          <h5  class="text-uppercase font-weight-bold">excellence</h5>
          <p class="mx-4">Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn font-weight-bold mb-4">LEARN MORE</button>
            
          
      </div>

</div>

   

  </section>
</template>

<script>
export default {
    name: 'QualityCardSection'

}
</script>

<style lang="scss" scoped>
@import './style/general.scss';

.mybg {
    background-color: #ebe9e7;
}

.myborder {
    border-top: 3px solid $askcolor;
    border-left: 1px solid #bcbcbd;
    border-right: 1px solid #bcbcbd;
    border-bottom: 1px solid #bcbcbd;
}

.feature-card {
    max-width: 300px;
    

}

.mybtn {
    background-color: #242b32;
    color: white;
}


img {
    width: 75%;
    height: 300px;
}

.bg-white {
    background-color: white;
}



</style>
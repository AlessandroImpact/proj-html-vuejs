<template>
  <section class=" mybg py-5 ">

      <div class=" d-flex justify-content-center align-items-center mx-5 bg-white">

      <div class="feature-card text-center">
           <p><i class="fa-solid fa-check check-icon"></i></p>
          <h5 class="text-uppercase">A global view</h5>
          <p>Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn-blue mb-5">LEARN MORE</button>

      </div>

      <div class="feature-card mx-5 text-center">
           <p><i class="fa-solid fa-check check-icon"></i></p>
          <h5  class="text-uppercase">Expert Lawyers</h5>
          <p>Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn-blue mb-5">LEARN MORE</button>
          
      </div>

      <div class="feature-card mx-5 text-center">
           <p><i class="fa-solid fa-check check-icon"></i></p>
          <h5  class="text-uppercase">Client Focus</h5>
          <p>Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn-blue mb-5">LEARN MORE</button>
          
      </div>

      <div class="feature-card text-center">
          <p><i class="fa-solid fa-check check-icon"></i></p>
          <h5  class="text-uppercase">Local Knowledge</h5>
          <p>Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn-blue mb-5">LEARN MORE</button>
          
      </div>

      </div>

  </section>
</template>

<script>
export default {
    name: 'FeatureSection'

}
</script>

<style lang="scss" scoped>
@import './style/general.scss';

.mybg {
    background-color: #ebe9e7;
    min-height: 400px;
}

.feature-card {
    max-width: 250px;
    border-top: 5px solid $askcolor;
    

}
.check-icon {
    color: $askcolor; 
}

.mybtn-blue {
    background-color: #30343a;
    color: white;
}



</style>
<template>
  <section class=" px-5 py-5 mybg">

      <div class="  d-flex justify-content-center align-items-center mx-2 bg-white py-5 myborder">

      <div class="feature-card mx-5 text-center">
           <p><i class="fa-solid fa-check check-icon"></i></p>
          <h5 class="text-uppercase ">who we are</h5>
          <p>Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn ">LEARN MORE</button>
    

      </div>

      <div class="feature-card mx-5 text-center">
           <p><i class="fa-solid fa-check check-icon"></i></p>
          <h5  class="text-uppercase font-weight-bold">what we do</h5>
          <p>Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn font-weight-bold">LEARN MORE</button>
           
          
      </div>

      <div class="feature-card mx-5 text-center">
           <p><i class="fa-solid fa-check check-icon"></i></p>
          <h5  class="text-uppercase font-weight-bold">where we work</h5>
          <p>Nullam fringilla tristique elit id
            varius ipsums. Lorem lacinia
            quam nec venenatis sadips dignissim.</p>
            <button class="btn mybtn font-weight-bold">LEARN MORE</button>
            
          
      </div>

</div>

   

  </section>
</template>

<script>
export default {
    name: 'MissionSection'

}
</script>

<style lang="scss" scoped>
@import './style/general.scss';

.mybg {
    background-color: #ebe9e7;
}

.myborder {
    border-top: 3px solid $askcolor;
}

.feature-card {
    max-width: 250px;
    
    

}

.mybtn {
    background-color: #242b32;
    color: white;
}





</style>
<template>
  
  <section class="text-center text-white py-5">

          <h3 class="text-uppercase">let's work toghether!</h3>

          <hr class="mx-auto my-5">

          <p class="font-weight-bold pb-5 mx-auto" >
              We work as a single united team with market leading firms around the world
              and give our clients the highest quality advice possible
          </p>

          <button class="btn my-btn text-white font-weight-bold ">MAKE ENQUIRY</button>

      

    

  </section>

</template>

<script>
export default {
    name: 'WorkTogether',
    

}
</script>

<style lang="scss" scoped>
@import './style/general.scss';

section {
    background-image: url("./images/where-we-work-parallax.jpg");
    background-size: cover;
    min-height: 400px;

}

.my-btn {
    background-color: #74a59e;
    font-weight: 600;
}

hr {
    width: 100px;
}

p {
    width: 600px;
    font-weight: 700;
   
}






</style>


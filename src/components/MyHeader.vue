<template>
  <section class="d-flex justify-content-center">
    <div class="logo d-flex justify-content-center align-items-center mx-5 p-3">
      <img src="./partial/images/avada-law-logo.png" alt="" />
    </div>

    <div class="my-head">
      <ul class="d-flex flex-row">
        <li v-for="item in items" :key="item.title">
          {{ item.title }}
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  name: "MyHeader",

  data() {
    
      return{ 
          items: [
        {
          title: "Home",
        },
        {
          title: "Who we are",
        },
        {
          title: "What we do",
        },
        {
          title: "Where we Work",
        },
        {
          title: "Careers",
        },
        {
          title: "News",
        },
        {
          title: "Contact",
        },
      ],
    
  }
  },

  methods: {},
};
</script>

<style lang="scss" scoped>
@import "./partial/style/general.scss";

section {
  height: 100px;
}

.logo {
  width: 25%;
  height: 100%;
}

.my-head {
  width: 75%;
}

ul{
    list-style-type: none;
    margin-top: 35px;
}

li {
    margin-left: 35px;
    color: #bcbcbd;
    cursor: pointer;
}

li:hover {
    color: $askcolor;
}
</style>

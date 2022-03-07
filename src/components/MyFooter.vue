<template>
  <section>
    
      <h5 class="px-5 pt-5">CALL OUR EXPERT TODAY 1.800.555.6789</h5>
    <div class="d-flex justify-content-between">
      <ul class="d-flex flex-row">
          <span v-html="copy"></span>
        <li v-for="item in items" :key="item.title">
          {{ item.title }}
        </li>
      </ul>

        <ul class="icons d-flex flex-row">
            <li><i class="fa-brands fa-facebook-square"></i></li>
             <li><i class="fa-brands fa-twitter-square"></i></li>
            <li><i class="fa-brands fa-instagram-square"></i></li>
            <li><i class="fa-brands fa-youtube-square"></i></li>
        </ul>


      </div>


    
  </section>
</template>

<script>
export default {
  name: "MyFooter",

  data() {
    return {

        copy: '&copy;',

      items: [
        {
          title: "Copyright 2012 - 2020  | ",
        },
        {
          title: "  Avada Theme by Theme Fusion  | ",
        },
        {
          title: "  All Rights Reserved  | ",
        },
        {
          title: "  Powered by Wordpress   ",
        },
      ],
    };
  },

  methods: {},
};
</script>

<style lang="scss" scoped>
@import "./partial/style/general.scss";

h5 {
  color: black;
  font-weight: 600;
}

span {
   margin-right: 0px;
   padding-right: 0px;
    color:#bcbcbd ;
}

ul {
    width: 70%;
  list-style-type: none;
  margin-top: 35px;
}

li {
  margin-left: 15px;
  color: #bcbcbd;
  cursor: pointer;
}

li:hover {
  color: $askcolor;
}

.icons {
    width: 30%;
    padding-left: 80px;
}
.icons li i {
    
    background-color: white;
    color:$askcolor;
    font-size: 30px;
}
</style>
<template>
    <MDBCarousel
    v-model="carousel2"
    :items="items2"
    :controls="false"
    :indicators="false"
  />
  <br><br>
  <h6><i>Pinkay & Kuro is established By Team of Anime & Manga Enthusiasts. At Pinkay & Kuro we promise you to offer best Quality & Price ratio products based on your favourite Anime & Japanese culture</i></h6>
 <br><br>
 <MDBRow>
    <MDBCol col="6"><h1><b>ABOUT OUR TEAM</b></h1><p>We a team full of entrepreneurs Enriched with many ideas which are in implementation . By supporting us you will help us as an artist as an family.</p></MDBCol>
    <MDBCol col="6"><h1><b>PREVIOUS WORKS</b></h1><p>We also worked with Rage and Comicon as marketing team and product design and are specialised In Designing modern Aesthetics which means what you see here is Handpicked by us with Totally new fresh and Modern Styles , You can be part of our small family we call " Pinkay & Kuro " just by supporting us by buying products from our site</p></MDBCol>
  </MDBRow>
  <MDBRow>
    <MDBCol sm="6"><h1><b>VISION</b></h1><p>What you wear or keep in possession is form of your self and very own expression. So at Pinkay & Kuro we ensure you to provide wide variety of Anime Products . Everything which is crafted with love and Culture.</p></MDBCol>
    <MDBCol sm="6"><h1><b>OUR PRIORITY AND GOALS</b></h1><p>Our goal in not only sell products but to build a community. We aim turn your purchase into an experience.</p></MDBCol>
  </MDBRow>

</template>

<script>
 import { ref } from "vue";
  import { MDBCarousel,MDBCol, MDBRow } from "mdb-vue-ui-kit";
  export default {
    components: {
      MDBCarousel,
       MDBCol,
      MDBRow
    },
    setup() {
      const items2 = [
        {
          src: "https://i.postimg.cc/fRbnWnQ9/SAVE-20211216-170137-1728x.webp",
          alt: "..."
        },
        {
          src: "https://i.postimg.cc/fRbnWnQ9/SAVE-20211216-170137-1728x.webp",
          alt: "..."
        },
        {
          src: "https://i.postimg.cc/fRbnWnQ9/SAVE-20211216-170137-1728x.webp",
          alt: "..."
        }
      ];
      const carousel2 = ref(0);
      return {
        items2,
        carousel2
      };
    }
  };
</script>

<style scoped>

.body{
      text-align: center;
  height: 150vh;
  background:linear-gradient(135deg, #8f0583, #c015cf, #ff00ea);
  z-index: 1;
}

</style>
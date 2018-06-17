<template>
    <div>
      <comming/>
      <!-- <the-header/>
      <gif/>
      <systems/>
      <main-image/>
      <the-footer/> -->
    </div>
  
</template>

<script>
import Comming from "@/components/Parallax/Comming.vue";
// import TheHeader from "@/components/TheHeader/TheHeader.vue";
// import Gif from "@/components/Parallax/Gif.vue";
// import MainImage from "@/components/Parallax/MainImage.vue";
// import Systems from "@/components/Systems/Systems.vue";
// import TheFooter from "@/components/TheFooter/TheFooter.vue";

export default {
  components: {
    Comming,
    // Gif,
    // MainImage,
    // Systems,
    // TheFooter
  },
  mounted() {
    $(".parallax").parallax();
    $(".button-collapse").sideNav();
  }
};
</script>

<style>
@font-face {
  font-family: "ttf";
  src: url(~/assets/font/Tr2n.ttf);
}

.ttf {
  font-family: ttf, sans-serif;
}
</style>

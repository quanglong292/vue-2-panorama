<template>
  <div id="panorama">
    <a-scene>
      <!-- <a-sky :src="panoramaImg"></a-sky> -->
      <a-sky src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/sechelt.jpg"></a-sky>
    </a-scene>
  </div>
</template>

<script>
// import panoramaImg from "@/assets/panorama-img.jpg";
import panoramaImg from "@/assets/pexels-pixabay-346286.jpg";
export default {
  name: "PanoramaView",
  props: {
    // panoramaImage: {
    //     type: String,
    //     required: true
    // }
  },
  data() {
    return {
      panoramaImg,
    };
  },
};
</script>

<style scoped>
#panorama {
  width: 100%;
  height: 100vh;
}
</style>

<!-- Add A-Frame library -->
<!-- <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>  -->

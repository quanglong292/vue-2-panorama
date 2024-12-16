<template>
  <div id="panorama">
    <a-scene embedded>
      <a-sky
        src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/sechelt.jpg"
      ></a-sky>
    </a-scene>
  </div>
</template>

<script>
import panoramaImg from "@/assets/pexels-pixabay-346286.jpg";
export default {
  name: "PanoramaView",
  data() {
    return {
      panoramaImg,
    };
  },
};
</script>

<style scoped>
#panorama {
  width: 50%;
  height: 50vh;
}

a-scene {
  width: 100%;
  height: 100%;
}
</style>

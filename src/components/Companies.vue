<template>
     <div class="px-4 lg:px-16 py-8">
  <div class="text-center my-9">
    <p class="text-xl lg:text-2xl text-black font-semibold">
      Trusted by Fortune 500. Used by 65,000+ companies and researchers worldwide
    </p>
  </div>
  <div class="grid grid-cols-3 md:grid-cols-4 lg:grid-cols-7 gap-4 justify-center items-center">
    <div v-for="(image, index) in images" :key="index" class="">
      <img :src="image.url" :style="image.styles" alt="images" />
    </div>
  </div>
</div>
</template>

<script>
export default {
  data() {
    return {
      images: [
        {
          url: "https://cdn.supervise.ly/img/bmw-full.150350e.png",
          styles: {
           width: "100px",
            height: "auto", 
         
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/resson.8103f95.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/HUK-COBURG.c977d50.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/Thornton-Thomasetti.46ad92d.jpg",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/engie.288d023.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/bigmate.b46c879.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/bitwise.1b06c96.png",
          styles: {
            width: "50px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/plant-and-food.2b03e36.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/raven.f43fc08.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/ucsf.210d328.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/cnh.6307774.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/exxact.2d423f8.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/rz.6d5191c.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/bentley.ba72ccb.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/nobel.be64cc6.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/pvel.f163ad9.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/carcutter.3dc948b.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/firemark.f4d8f41.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/caresyntax.d2f0e47.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/eeve.fee0410.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
        {
          url: "https://cdn.supervise.ly/img/obb.3274928.png",
          styles: {
            width: "100px",
            height: "auto",
           
          },
        },
      ],
    };
  },
};
</script>



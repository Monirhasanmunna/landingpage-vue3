<script setup>
  const title = 'Gallery'
  const subTitle = 'Check our Gallery'

  const image1 = './src/assets/img/gallery/gallery-1.jpg'
  const image2 = './src/assets/img/gallery/gallery-2.jpg'
  const image3 = './src/assets/img/gallery/gallery-3.jpg'
  const image4 = './src/assets/img/gallery/gallery-4.jpg'
  const image5 = './src/assets/img/gallery/gallery-5.jpg'
  const image6 = './src/assets/img/gallery/gallery-6.jpg'
  const image7 = './src/assets/img/gallery/gallery-7.jpg'
  const image8 = './src/assets/img/gallery/gallery-8.jpg'
</script>

<template>

<section id="gallery" class="gallery">
      <div class="container">

        <div class="section-title" data-aos="fade-up">
          <h2>{{ title }}</h2>
          <p>{{ subTitle }}</p>
        </div>

        <div class="row g-0" data-aos="fade-left">

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="100">
              <a v-bind:href="image1" class="gallery-lightbox">
                <img v-bind:src="image1" alt="" class="img-fluid">
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="150">
              <a :href="image2" class="gallery-lightbox">
                <img :src="image2" alt="" class="img-fluid">
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="200">
              <a :href="image3" class="gallery-lightbox">
                <img :src="image3" alt="" class="img-fluid">
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="250">
              <a :href="image4" class="gallery-lightbox">
                <img :src="image4" alt="" class="img-fluid">
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="300">
              <a :href="image5" class="gallery-lightbox">
                <img :src="image5" alt="" class="img-fluid">
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="350">
              <a :href="image6" class="gallery-lightbox">
                <img :src="image6" alt="" class="img-fluid">
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="400">
              <a :href="image7" class="gallery-lightbox">
                <img :src="image7" alt="" class="img-fluid">
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item" data-aos="zoom-in" data-aos-delay="450">
              <a :href="image1" class="gallery-lightbox">
                <img :src="image1" alt="" class="img-fluid">
              </a>
            </div>
          </div>

        </div>

      </div>
    </section>

</template>

<style scoped>

</style>
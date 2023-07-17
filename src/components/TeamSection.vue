<script setup>
  import person from '../data/teamSection'

  const title = 'Our Great Team'
  const subTitle = 'Team'
  
</script>

<template>

<section id="team" class="team">
      <div class="container">

        <div class="section-title" data-aos="fade-up">
          <h2>{{ subTitle }}</h2>
          <p>{{ title }}</p>
        </div>

        <div class="row" data-aos="fade-left">

          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="zoom-in" data-aos-delay="100">
              <div class="pic"><img :src="person[0].image" class="img-fluid" alt=""></div>
              <div class="member-info">
                <h4>{{ person[0].name }}</h4>
                <span>{{ person[0].designation }}</span>
                <div class="social">
                  <a href="#"><i class="bi bi-twitter"></i></a>
                  <a href="#"><i class="bi bi-facebook"></i></a>
                  <a href="#"><i class="bi bi-instagram"></i></a>
                  <a href="#"><i class="bi bi-linkedin"></i></a>
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="zoom-in" data-aos-delay="100">
              <div class="pic"><img :src="person[1].image" class="img-fluid" alt=""></div>
              <div class="member-info">
                <h4>{{ person[1].name }}</h4>
                <span>{{ person[1].designation }}</span>
                <div class="social">
                  <a href="#"><i class="bi bi-twitter"></i></a>
                  <a href="#"><i class="bi bi-facebook"></i></a>
                  <a href="#"><i class="bi bi-instagram"></i></a>
                  <a href="#"><i class="bi bi-linkedin"></i></a>
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="zoom-in" data-aos-delay="100">
              <div class="pic"><img :src="person[2].image" class="img-fluid" alt=""></div>
              <div class="member-info">
                <h4>{{ person[2].name }}</h4>
                <span>{{ person[2].designation }}</span>
                <div class="social">
                  <a href="#"><i class="bi bi-twitter"></i></a>
                  <a href="#"><i class="bi bi-facebook"></i></a>
                  <a href="#"><i class="bi bi-instagram"></i></a>
                  <a href="#"><i class="bi bi-linkedin"></i></a>
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-3 col-md-6">
            <div class="member" data-aos="zoom-in" data-aos-delay="100">
              <div class="pic"><img :src="person[3].image" class="img-fluid" alt=""></div>
              <div class="member-info">
                <h4>{{ person[3].name }}</h4>
                <span>{{ person[3].designation }}</span>
                <div class="social">
                  <a href="#"><i class="bi bi-twitter"></i></a>
                  <a href="#"><i class="bi bi-facebook"></i></a>
                  <a href="#"><i class="bi bi-instagram"></i></a>
                  <a href="#"><i class="bi bi-linkedin"></i></a>
                </div>
              </div>
            </div>
          </div>

        </div>

      </div>
    </section>

</template>

<style scoped>

</style>
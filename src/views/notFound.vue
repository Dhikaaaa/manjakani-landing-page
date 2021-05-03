<template>
  <div>
    <div class="position-relative">
      <!-- shape Hero -->
      <section class="section-shaped my-0">
        <div class="shape shape-style-1 shape-default">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
        </div>

        <div class="container shape-container d-flex">
          <div class="col px-0">
            <div class="row justify-content-center">
              <div class="col-md-6 my-5">
                <img v-lazy="'img/ill/404.svg'" class="img-center img-fluid" />
              </div>
              <div class="col-lg-12 my-5">
                <h1 class="display-3 text-white text-center">
                  Maaf
                  <span>Halaman yang anda cari tidak ditemukan</span>
                </h1>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 1st Hero Variation -->
    </div>
  </div>
</template>

<style scoped></style>

<script>
export default {
  name: 'notFound',
  components: {},
};
</script>

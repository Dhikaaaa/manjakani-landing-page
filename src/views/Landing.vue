<template>
  <div>
    <div class="position-relative">
      <!-- shape Hero -->
      <section class="section-shaped my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
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
            <div class="row align-items-center">
              <div class="col-lg-8">
                <h1 class="display-3 text-white">
                  Miss V Manjakani Soap
                  <span>Sabun Kewanitaan Masa Kini</span>
                </h1>
                <p class="lead text-justify text-white">
                  Rawat diri, rawat tubuh dan paling penting rawat juga area kewanitaan. Karena area kewanitaan yang terawat menentukan kepuasan biologis pasangan. Kini ada rekomendasi perawatan area kewanitaan terbaik dan terlaris salah
                  satunya adalah <strong>Sabun Manjakani </strong> produksi khusus untuk Miss V anda
                </p>

                <a href="https://api.whatsapp.com/send?phone=6289621873378&text=Pesan%20sabun%20Manjakani%20mumpung%20promo%20Rp.%20100.000%20dapat%203pcs" target="_blank">
                  <base-button tag="button" href="" type="dark" class="my-5">
                    Pesan Sekarang
                  </base-button>
                </a>
              </div>
              <div class="col-lg-4">
                <div class="transform-perspective-right">
                  <img v-lazy="'img/theme/img-jumbotron.jpg'" alt="Manjakani Soap" class="img-thumbnail mb-2" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 1st Hero Variation -->
    </div>

    <!-- Card Info -->
    <section class="section section-lg pt-lg-0 mt--200">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-12">
            <div class="row row-grid justify-content-center">
              <div class="col-lg-4">
                <card class="border-0" hover shadow body-classes="py-5">
                  <icon name="ni ni-shop" type="success" rounded class="mb-4"> </icon>
                  <h6 class="text-success text-uppercase">Miss V Manjakani Soap</h6>
                  <p class="description mt-3 text-justify">Miss V Manjakani Soap merupakan sabun kewanitaan masa kini. Sabun 2 in 1 selain merawat area kewanitaan juga bisa digunakan untuk memutihkan seluruh badan.</p>
                  <img v-lazy="'img/theme/galeri-1.jpg'" alt="galeri 1" class="img-center img-fluid" />
                </card>
              </div>

              <div class="col-lg-4">
                <card class="border-0" hover shadow body-classes="py-5">
                  <icon name="ni ni-favourite-28" type="warning" rounded class="mb-4"> </icon>
                  <h6 class="text-warning text-uppercase">Komposisi dan Bahan</h6>
                  <p class="description mt-3 text-justify">
                    Miss V Manjakani Soap merupakan sabun kewanitaan pertama yang mengandung bahan bahan alami seperti <strong>Buah Manjakani, Minyak Zaitun, Daun Sirih, dan Susu.</strong> 100% bahan alami dan tentunya aman untuk segala
                    kalangan baik Remaja atau Ibu Hamil & Menyusui
                  </p>
                  <img v-lazy="'img/theme/galeri-4.jpg'" alt="galeri 2" class="img-center img-fluid" />
                </card>
              </div>

              <div class="col-lg-4">
                <card class="border-0" hover shadow body-classes="py-5">
                  <icon name="ni ni-tag" type="info" rounded class="mb-4"> </icon>
                  <h6 class="text-info text-uppercase">Cara Penggunaan</h6>
                  <p class="description mt-3 text-justify">
                    Ambil sabun, basahi dengan sedikit air hingga berbusa lalu usap pada area Miss V atau bisa juga digunakan untuk seluruh badan, selanjutnya diamkan beberapa menit lalu bilas hingga bersih
                  </p>
                  <img v-lazy="'img/theme/galeri-3.jpg'" alt="galeri 3" class="img-center img-fluid" />
                </card>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Card Info -->

    <!-- Promo -->
    <section class="section section-shaped my-0 overflow-hidden" id="promo">
      <div class="shape shape-style-1 bg-gradient-default shape-skew">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="container pt-lg pb-300">
        <hr class="bg-white" />
        <div class="row text-center justify-content-center">
          <div class="col-lg-10">
            <h2 class="display-3 text-white">PROMO TERBATAS</h2>
            <h3 class="display-4 text-white">Beli 3 Hanya 100.000 Rupiah</h3>
            <div class="col-lg-8 offset-lg-2">
              <img v-lazy="'img/theme/galeri-7.jpg'" alt="galeri 3" class="img-fluid floating" />
            </div>
            <p class="lead text-white ">
              Harga yang semula
              <br /><span class=" display-1 text-through">Rp. 150.000</span><br />
              kini bisa anda dapatkan seharga <br /><span class="display-1">Rp. 100.000</span><br />
              Buruan sebelum kehabisan !!!
            </p>
          </div>
        </div>
        <hr class="bg-white" />
        <h2 class="display-3 text-white text-center mb-5">Jangan Khawatir Belanja di Toko Kami</h2>
        <div class="row row-grid mt-5">
          <div class="col-lg-4">
            <icon name="ni ni-satisfied" size="lg" gradient="white" shadow round color="primary"></icon>
            <h5 class="text-white mt-3">Kepuasan Pelanggan</h5>
            <p class="text-white mt-3 text-justify">
              Kami akan memberikan pelayanan terbaik mulai dari Admin yang tersedia 24 jam. Melayani pembelian atau hanya ingin tanya seputar produk kami. Semua kami lakukan karena pelanggan merupakan <strong>Prioritas Utama</strong> bagi
              kami. Cek langsung testimoni dan feedback yang kami terima dari pelanggan.
            </p>
          </div>
          <div class="col-lg-4">
            <icon name="ni ni-bag-17" size="lg" gradient="white" shadow round color="primary"></icon>
            <h5 class="text-white mt-3">100% Original Produk</h5>
            <p class="text-white mt-3 text-justify">
              Produk yang kami jual <strong>100% Original</strong> bukan barang tiruan ataupun reject. mengandung bahan bahan alami seperti <strong>Buah Manjakani, Minyak Zaitun, Daun Sirih, dan Susu.</strong> 100% bahan alami dan tentunya
              aman untuk segala kalangan baik Remaja atau Ibu Hamil & Menyusui
            </p>
          </div>
          <div class="col-lg-4">
            <icon name="ni ni-delivery-fast" size="lg" gradient="white" shadow round color="primary"></icon>
            <h5 class="text-white mt-3">Proses Transaksi</h5>
            <p class="text-white mt-3 text-justify">
              Kami akan langsung mengirimkan barang setelah pemesanan dilakukan dan bukti transfer sudah dikirim. Proses pengiriman barang menggunakan layanan ekspedisi <strong>Terbaik dan Tercepat</strong>. Selain transfer kami juga
              menerima pemesanan dengan sistem bayar ditempat atau biasa disebut COD.
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Promo -->

    <!-- Manfaat -->
    <section class="section section-lg" id="manfaat">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-4 order-md-2">
            <img v-lazy="'img/theme/klikbait.jpg'" class="img-fluid floating" />
          </div>
          <div class="col-md-8 order-md-1">
            <div class="pr-md-5">
              <icon name="ni ni-bullet-list-67" class="mb-3" size="lg" type="success" shadow rounded></icon>
              <h3>Manfaat Yang Didapat</h3>
              <ul class="list-unstyled mt-3">
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menghilangkan Keputihan</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menjaga Keseimbangan pH kewanitaan</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menghilangkan bau tak sedap pada area kewanitaan</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menghilangkan gatal gatal pada area kewanitaan</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menghilangkan jamur dan bakteri pada area kewanitaan</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Mengharumkan dan memberikan kesegaran untuk area kewanitaan</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menghilangkan lendir berlebih (becek)</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Mengencangkan dan memperbesar payudara</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menambah keharmonisan suami istri</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menghilangkan bau badan tak sedap</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Membersihkan dan memutihkan area lipatan tubuh</h6>
                  </div>
                </li>
                <li class="py-1">
                  <div class="d-flex align-items-center">
                    <badge type="success" circle class="mr-3" icon="ni ni-fat-delete"></badge>
                    <h6 class="mb-0">Menghilangkan gatal gatal pada kulit badan</h6>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Manfaat  -->

    <!-- Testimoni -->
    <section class="section bg-secondary" id="feedback">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-6">
            <div class="card bg-default shadow border-0 overflow-hidden transform-perspective-left">
              <div class="p-5">
                <video class="embed-responsive" src="video/video.mp4" autoplay controls></video>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="pl-md-5">
              <icon name="ni ni-settings" class="mb-5" size="lg" shadow rounded></icon>
              <h3>Feedback customers</h3>
              <p class="lead">BPOM Na 18200500771</p>
              <p>Love banget <badge type="danger" icon="ni ni-favourite-28"></badge></p>
              <p>Sabun Manjakani bukan untuk Miss V saja!! Untuk badan juga bisa loo. Badan terasa segar dan harum.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Testimoni -->

    <!-- Galeri -->
    <section class="section section section-shaped my-0 overflow-hidden" id="galeri">
      <div class="shape shape-style-1 bg-gradient-warning shape-skew">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="container py-0">
        <div class="row row-grid align-items-center">
          <div class="col-md-6 order-lg-2 ml-lg-auto">
            <div class="position-relative pl-md-6">
              <img v-lazy="'img/ill/gallery.svg'" class="img-center img-fluid" />
            </div>
          </div>
          <div class="col-lg-6 order-lg-1">
            <div class="d-flex px-3">
              <div>
                <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow rounded></icon>
              </div>
              <div class="pl-4">
                <h4 class="display-3 text-white">Galeri</h4>
              </div>
            </div>
            <div class="scroll py-4 my-5">
              <card shadow class="shadow-lg--hover mt-4">
                <h5 class="title text-warning text-center">Manjakani Soap</h5>
                <div class="d-flex px-3">
                  <img v-lazy="'img/theme/galeri-2.jpg'" alt="galeri 2" class="img-center img-fluid" />
                </div>
              </card>

              <card shadow class="shadow-lg--hover mt-4">
                <h5 class="title text-warning text-center">Manjakani Soap</h5>
                <div class="d-flex px-3">
                  <img v-lazy="'img/theme/galeri-5.jpg'" alt="galeri 3" class="img-center img-fluid" />
                </div>
              </card>

              <card shadow class="shadow-lg--hover mt-4">
                <h5 class="title text-warning text-center">Manjakani Soap</h5>
                <div class="d-flex px-3">
                  <img v-lazy="'img/theme/galeri-6.jpg'" alt="galeri 4" class="img-center img-fluid" />
                </div>
              </card>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Galeri -->

    <!-- Testimoni -->
    <section class="section section-lg" id="testimoni">
      <div class="container">
        <div class="row justify-content-center text-center mb-lg">
          <div class="col-lg-8">
            <h2 class="display-3">Testimoni</h2>
          </div>
        </div>
        <card gradient="dark" no-body shadow-size="lg" class="border-0">
          <div class="p-5">
            <div class="row align-items-center justify-content-center">
              <div class="col-lg-4  mb-4">
                <img v-lazy="'img/theme/testi-1.jpg'" alt="testi 1" class="img-center img-fluid" />
              </div>
              <div class="col-lg-4 mb-4">
                <img v-lazy="'img/theme/testi-2.jpg'" alt="testi 2" class="img-center img-fluid" />
              </div>
              <div class="col-lg-4 mb-4">
                <img v-lazy="'img/theme/testi-3.jpg'" alt="testi 3" class="img-center img-fluid" />
              </div>
            </div>
            <div class="row align-items-center justify-content-center">
              <div class="col-lg-6 mb-4">
                <img v-lazy="'img/theme/testi-4.jpg'" alt="testi 4" class="img-center img-fluid" />
              </div>
            </div>
            <div class="row align-items-center justify-content-center">
              <div class="col-lg-6 mb-4">
                <img v-lazy="'img/theme/testi-5.jpg'" alt="testi 5" class="img-center img-fluid" />
              </div>
              <div class="col-lg-6 mb-4">
                <img v-lazy="'img/theme/testi-6.jpg'" alt="testi 6" class="img-center img-fluid" />
              </div>
            </div>
            <div class="row align-items-center justify-content-center">
              <div class="col-lg-8 mb-4">
                <img v-lazy="'img/theme/testi-7.jpg'" alt="testi 7" class="img-center img-fluid" />
              </div>
            </div>
            <div class="row align-items-center justify-content-center">
              <div class="col-lg-6 mb-4">
                <img v-lazy="'img/theme/testi-8.jpg'" alt="testi 8" class="img-center img-fluid" />
              </div>
              <div class="col-lg-6 mb-4">
                <img v-lazy="'img/theme/testi-9.jpg'" alt="testi 9" class="img-center img-fluid" />
              </div>
            </div>
            <div class="row align-items-center justify-content-center">
              <div class="col-lg-8 mb-4">
                <img v-lazy="'img/theme/testi-10.jpg'" alt="testi 10" class="img-center img-fluid" />
              </div>
            </div>
          </div>
        </card>
      </div>
    </section>
    <!-- Akhir Testimoni -->

    <!-- <section class="section section-lg pt-lg-0 section-contact-us">
      <div class="container">
        <div class="row justify-content-center mt--300">
          <div class="col-lg-8">
            <card gradient="secondary" shadow body-classes="p-lg-5">
              <h4 class="mb-1">Want to work with us?</h4>
              <p class="mt-0">Your project is very important to us.</p>
              <base-input class="mt-5" alternative placeholder="Your name" addon-left-icon="ni ni-user-run"> </base-input>
              <base-input alternative placeholder="Email address" addon-left-icon="ni ni-email-83"> </base-input>
              <base-input class="mb-4">
                <textarea class="form-control form-control-alternative" name="name" rows="4" cols="80" placeholder="Type a message..."></textarea>
              </base-input>
              <base-button type="default" round block size="lg">
                Send Message
              </base-button>
            </card>
          </div>
        </div>
      </div>
    </section> -->
  </div>
</template>

<style scoped>
.scroll {
  height: 700px;
  overflow: scroll;
  overflow-x: hidden;
}

::-webkit-scrollbar {
  width: 0px; /* remove scrollbar space */
}

.text-through {
  text-decoration: line-through;
}
</style>

<script>
export default {
  name: 'home',
  components: {},
};
</script>

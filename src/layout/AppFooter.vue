<template>
  <footer class="footer bg-default text-white">
    <div class="container">
      <div class="row row-grid align-items-center my-md">
        <div class="col-lg-6">
          <h3 class="text-primary text-white font-weight mb-2">Terima Kasih!</h3>
          <h4 class="mb-0 text-white font-weight-light">Silakan Kunjungi Sosial Media Kami</h4>
        </div>
        <div class="col-lg-6 text-lg-center btn-wrapper">
          <a target="_blank" rel="noopener" href="https://www.facebook.com/vaye.beautycare/" class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip" data-original-title="Like us">
            <i class="fa fa-facebook-square"></i>
          </a>
          <a
            target="_blank"
            rel="noopener"
            href="https://instagram.com/vay_e.beautycare.official?igshid=7rz1yr1djo9a"
            class="btn btn-neutral btn-icon-only btn-instagram btn-lg btn-round"
            data-toggle="tooltip"
            data-original-title="Follow us"
          >
            <i class="fa fa-instagram"></i>
          </a>
          <a
            target="_blank"
            rel="noopener"
            href="https://api.whatsapp.com/send?phone=6289621873378&text=Pesan%20sabun%20Manjakani%20mumpung%20promo%20Rp.%20100.000%20dapat%203pcs"
            class="btn btn-success btn-icon-only btn-round btn-lg"
            data-toggle="tooltip"
            data-original-title="Hubungi lewat WhatsApp"
          >
            <i class="fa fa-whatsapp"></i>
          </a>
        </div>
      </div>
      <hr />
      <div class="row align-items-center justify-content-center">
        <div class="col-md-12">
          <div class="copyright">&copy; {{ year }} <a href="https://www.creative-tim.com" target="_blank" rel="noopener">Creative Tim</a> & <a href="https://www.binarcode.com" target="_blank" rel="noopener">Binar Code</a></div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>

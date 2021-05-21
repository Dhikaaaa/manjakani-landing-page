<template>
  <header class="header-global">
    <base-nav class="navbar-main" transparent type="" effect="light" expand>
      <router-link slot="brand" class="navbar-brand d-flex" to="/">
        <img src="img/brand/white.png" alt="logo" class="navbar-brand" />
        <!-- <h6 class="text-white mt-1">Manjakani</h6> -->
      </router-link>

      <div class="row" slot="content-header" slot-scope="{ closeMenu }">
        <div class="col-8 collapse-brand">
          <!-- <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"> -->
          <img src="img/brand/black.png" class="navbar-brand" />
          <!-- <h6 class="heading text-primary">Manjakani</h6> -->
          <!-- </a> -->
        </div>
        <div class="col-4 collapse-close">
          <close-button @click="closeMenu"></close-button>
        </div>
      </div>

      <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
        <router-link to="/" class="nav-link">Home</router-link>
        <router-link to="/#manfaat" class="nav-link">Manfaat</router-link>
        <router-link to="/#feedback" class="nav-link">Feedback</router-link>
        <router-link to="/#testimoni" class="nav-link">Testimoni</router-link>
      </ul>
      <ul class="navbar-nav align-items-lg-center ml-lg-auto">
        <li class="nav-item">
          <a class="nav-link nav-link-icon" href="https://www.facebook.com/vaye.beautycare/" target="_blank" rel="noopener" data-toggle="tooltip" title="Like us on Facebook">
            <i class="fa fa-facebook-square"></i>
            <span class="nav-link-inner--text d-lg-none">Facebook</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-link-icon" href="https://instagram.com/vay_e.beautycare.official?igshid=7rz1yr1djo9a" target="_blank" rel="noopener" data-toggle="tooltip" title="Follow us on Instagram">
            <i class="fa fa-instagram"></i>
            <span class="nav-link-inner--text d-lg-none">Instagram</span>
          </a>
        </li>
        <li class="nav-item">
          <a
            class="nav-link nav-link-icon"
            href="https://api.whatsapp.com/send?phone=6289621873378&text=Pesan%20sabun%20Manjakani%20mumpung%20promo%20Rp.%20100.000%20dapat%203pcs"
            target="_blank"
            rel="noopener"
            data-toggle="tooltip"
            title="Follow us on Instagram"
          >
            <i class="fa fa-whatsapp"></i>
            <span class="nav-link-inner--text d-lg-none">WhatsApp</span>
          </a>
        </li>
      </ul>
    </base-nav>
  </header>
</template>

<style>
.navbar-brand {
  width: 100px;
  height: 100px !important;
}
</style>

<script>
import BaseNav from '@/components/BaseNav';
import BaseDropdown from '@/components/BaseDropdown';
import CloseButton from '@/components/CloseButton';

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown,
  },
};
</script>
<style></style>

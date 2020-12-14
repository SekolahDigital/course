<template>
  <main id="app">
    <section>
        <div class="row">
          <div class="col-1 bg-primary" style="min-height:625px">
            <div class="text-center">
              <router-link class="navbar-brand" to="/dashboard">
                <h5 class="font-weight-bold mt-4" style="line-height:20px;color:#222831;margin-right:-25px">Sekolah<br>Digital</h5>
              </router-link>
            </div>
          </div>
          <div class="col-11">
            <nav class="navbar navbar-expand-lg navbar-dark" style="z-index:99 !important;margin-left:-20px">
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-5">
                  <li class="nav-item">
                    <router-link class="nav-link" active-class="active" to="/dashboard">PROGRESSKU</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" active-class="active" to="/dashboard/kelasku">KELASKU</router-link>
                  </li>
                  <li class="nav-item">
                    <router-link class="nav-link" active-class="active" to="/dashboard/karyaku">KARYAKU</router-link>
                  </li>
                  <li class="nav-item login-nav" style="margin-right:90px">
                    <div class="row">
                      <img src="https://scontent-xsp1-2.cdninstagram.com/v/t51.2885-15/e35/67632001_475641503272345_8035766879171348296_n.jpg?_nc_ht=scontent-xsp1-2.cdninstagram.com&_nc_cat=101&_nc_ohc=pT7e4dXl_bwAX-4PSrh&tp=1&oh=dac6f5829afcb9a26e12fdd177c42907&oe=5FFF5AE3" alt="" class="rounded-circle img-fluid" width="50">
                      <p
                        class="nav-link font-weight-bold my-0"
                      >Rafli Ramadhan</p>
                    </div>
                  </li>
                </ul>
              </div>
            </nav>
            <section>
              <div class="container">
                <h4 class="mb-0 font-weight-600">Progress Kelas</h4>
                <p class="text-muted">ini adalah kelas yang kamu ikuti</p>
                <div class="row">
                  <div class="col-6">
                    <div class="item-kelas py-2 pb-3 border bg-white rounded px-4" v-for="kelas in 3" :key="kelas.index">
                      <p class="mb-2 py-2 font-weight-600">Fullstack Developer</p>
                      <div class="progress mb-3">
                        <div
                          class="progress-bar"
                          role="progressbar"
                          aria-valuemin="0"
                          aria-valuemax="100"
                        >0%</div>
                      </div>
                      <router-link
                        to="kelas"
                        class="btn mr-2 btn-sm btn-dark font-weight-600"
                      >LANJUTKAN BELAJAR</router-link>
                      <span>
                        <router-link to="asd"
                          class="btn btn-sm btn-outline-primary font-weight-600"
                        >CETAK SERTIFIKAT</router-link>
                      </span>
                    </div>
                  </div>
                 <div class="offset-lg-1 col-lg-5">
                    <div>
                      <h5 class="font-weight-600 mb-0">Terakhir Dipelajari</h5>
                      <p class="text-muted">Ayo Selesaikan kelasmu</p>
                    </div>
                     <div class="item-kelas history py-2 pb-3 border rounded px-4 bg-white">
                        <p class="font-weight-600 mb-0">Installasi Tools</p>
                        <p class="text-muted mb-2">Fullstack Developer</p>
                        <router-link
                          to="a"
                          class="btn mr-2 btn-sm btn-dark px-4 font-weight-600"
                        >LANJUT</router-link>
                      </div>
                  </div>
                </div>
              </div>
            </section>
            </div>
          </div>
    </section>
  </main>
</template>

<script>
import "~/assets/style.css"
export default {

}
</script>

<style>

</style>
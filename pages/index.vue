<template>
<main id="app">
  <section>
    <div class="container">
      <Navbar/>
    </div>
  </section>

  <section>
    <div class="container">
      <div class="row">
        <div class="col-lg-8 mt-5" style="margin-top:100px">
          <h1 class="text-redhat">Buat Mimpimu Jadi Kenyataan.</h1>
          <p class="text-redhat" style="width:580px;font-size:24px">Pelajari kelas-kelas terbaik yang kita sediakan <br> untuk menjenjang karir atau sekedar membuat karya. kami tunggu dikelas!</p>
           <input
              type="text"
              class="form-control border border-dark py-4 px-4 col-lg-9 col-12 mt-5"
              placeholder="Cari kelas ex: Javascript"
            />
        </div>
        <div class="col-lg-4">
          <img src="~/assets/svg/home_bottom.svg" class="position-absolute" style="top:-100px;left:-70px">
          <img src="~/assets/svg/home.svg" class="position-absolute">
        </div>
      </div>
    </div>
  </section>

  <section style="margin-top: 400px" class="mb-5">
    <div class="container">
      <h2 class="font-weight-bold">Kelas Rekomendasi</h2>
      <p>Rekomendasi kami untuk kamu yang suka belajar hal baru.</p>
      <no-ssr placeholder="Loading...">
        <carousel :per-page="4" >
          <slide>
            <DaftarKelas/>
          </slide>
          <slide>
            <DaftarKelas/>
          </slide>
          <slide>
            <DaftarKelas/>
          </slide>
          <slide>
            <DaftarKelas/>
          </slide>
          <slide>
            <DaftarKelas/>
          </slide>
          <slide>
            <DaftarKelas/>
          </slide>
          <slide>
            <DaftarKelas/>
          </slide>
        </carousel>
      </no-ssr>
    </div>
  </section>

  <section  class="mb-5">
    <div class="container">
      <h2 class="font-weight-bold">Kelas-Kelas Kami</h2>
      <p>Daftar kelas-kelas kami yang mungkin anda sukai.</p>
      <div class="kategori-button mb-5">
        <button class="btn btn-dark">PROGRAMMING</button>
        <button class="btn">SOFT SKILL</button>
        <button class="btn">MEMASAK</button>
      </div>

      <div class="daftar-kelas-kami d-flex flex-wrap justify-content-between" style="width:1036px;">
        <DaftarKelasKami/>
        <DaftarKelasKami/>
        <DaftarKelasKami/>
        <DaftarKelasKami/>
        <DaftarKelasKami/>
        <DaftarKelasKami/>
      </div>
      
     
    </div>
  </section>

  <BenefitSection/>
  <KeunggulanSection/>
  <Footer/>
</main>
</template>

<script>
import "~/assets/style.css"
export default {
 
};
</script>

<style>

</style>

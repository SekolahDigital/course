<template>
<main id="app">
  <section>
    <div class="container">
      <Navbar/>
    </div>
  </section>

  <section style="margin-top:110px">
    <div class="container">
      <div class="row justify-content-center text-center">
        <div class="col-lg-8 col-12 col-sm-12">
          <h1 class="text-redhat">Direktori Kelas</h1>
          <p style="font-size:18px">Update kemampuan kamu di era digital ini</p>
          <div class="row justify-content-center">
            <div class="col-lg-8 col-12">
              <input
                type="text"
                class="form-control border border-dark py-4 mt-3 px-4"
                placeholder="Cari kelas ex: Javascript"
              />
            </div>
          </div>

          

        </div>

        <div class="kategori-button my-5">
            <button class="btn btn-dark">PROGRAMMING</button>
            <button class="btn">SOFT SKILL</button>
            <button class="btn">MEMASAK</button>
          </div>
      </div>
    </div>
  </section>

  <section class="mb-5">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-12 col-sm-12 col-12">
          <div class="daftar-kelas-kami d-flex flex-wrap justify-content-between">
            <DaftarKelasKami/>
            <DaftarKelasKami/>
            <DaftarKelasKami/>
            <DaftarKelasKami/>
            <DaftarKelasKami/>
            <DaftarKelasKami/>
          </div>
        </div>
      </div>
      
     
    </div>
  </section>

  <BenefitSection/>
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

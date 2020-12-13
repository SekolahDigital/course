<template>
<main id="app">
  <section>
  <div class="container">
    <Navbar/>
  </div>
  </section>

  <section style="margin-top:70px">
    <div class="container">
      <div class="row justify-content-center text-center">
        <div class="col-12 col-lg-8 col-sm-12">
          <h1 class="text-redhat">Perjalanan Jurnalmu</h1>
          <p>Pilih jurnal belajarmu untuk menjenjang kakir</p>
           <div class="row justify-content-center" style="margin-top:-20px">
            <div class="col-lg-8 col-12">
              <input
                type="text"
                class="form-control border border-dark py-4 mt-3 px-4"
                placeholder="Cari kelas ex: Javascript"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section style="margin-top:60px">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-sm-12 col-md-8 col-lg-11 col-12">
          <div class="d-flex flex-wrap justify-content-between">
            <RoadmapKelas/>
            <RoadmapKelas/>
            <RoadmapKelas/>
            <RoadmapKelas/>
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
export default {

}
</script>

<style>

</style>
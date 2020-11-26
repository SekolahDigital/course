<template>
  <section class="keunggulan py-5 border-top">
    <div class="mt-5 container text-purple">
      <h2 class="pb-5 text-center">Keunggulan Belajar di SekolahDigital</h2>
      <div class="row">
        <div class="col-lg-4 col-md-6" v-for="unggul in keunggulan" :key="unggul.index">
          <Keunggulan :desc="unggul.isi" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { mapState } from "vuex";
export default {
  name: "KeunggulanSection",
  computed: {
    ...mapState(["keunggulan"])
  }
};
</script>

<style>
</style>
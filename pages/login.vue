<template>
  <main id="app">
    <div class="container mb-5">
      <div class="row justify-content-center" style="margin-top:80px;margin-bottom:68px">
        <div class="col-lg-8 col-12 col-sm-12 col-md-10">
          <div class="text-center">
            <h2 class="font-weight-bold">Login</h2>
            <p>belum punya akun? <router-link to="daftar">silakan buat dulu</router-link></p>
          </div>
          <div class="row justify-content-center">
            <div class="col-lg-6">
              <div class="mb-3">
                <label for="email">Email Address</label>
                <input type="text" class="form-control border" placeholder="Email Address" id="email">
              </div>
              <div class="mb-3">
                <label for="password">Password</label>
                <input type="password" class="form-control border" placeholder="Password" id="password">
              </div>
              <router-link to="dashboard" class="btn btn-dark form-control mb-2 font-weight-bold">LOGIN</router-link>
              <div class="text-right"><router-link to="lupa">Lupa Password?</router-link></div>
              <hr>
              <button class="form-control mb-2 btn border">MASUK DENGAN GOOGLE</button>
              <button class="form-control mb-2 btn border">MASUK DENGAN GITHUB</button>
            </div>
          </div>

        </div>
      </div>
    </div>
  </main>
</template>

<script>
import "~/assets/style.css"
export default {

}
</script>

<style>

</style>
<template>
   <nav class="navbar navbar-expand-lg navbar-dark" style="z-index:99 !important">
      <router-link class="navbar-brand" to="/">
        <h4 class="font-weight-bold" style="line-height:20px">Sekolah<br>Digital</h4>
      </router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-5">
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/kelas">KELAS</router-link>
          </li>
          <!-- <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/mading">MADING</router-link>
          </li> -->
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/roadmap">ROADMAP</router-link>
          </li>
          <!-- <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/cart">CART</router-link>
          </li> -->
          <!-- <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/wishlist">WISHLIST</router-link>
          </li> -->
    
          <li class="nav-item login-nav">
            <router-link
              class="nav-link btn btn-dark login font-weight-bold"
              active-class="active"
              to="/login"
            >LOGIN</router-link>
            
          </li>
        </ul>
      </div>
   </nav>
</template>

<script>
export default {
 name: "Navbar"
}
</script>
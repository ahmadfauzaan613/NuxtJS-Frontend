<template>
  <div class="navmenu">
    <div class="container">
      <b-navbar toggleable="lg" type="dark">
        <b-navbar-brand href="#"
          ><img
            src="@/assets/images/headeryesdok.png"
            alt=""
            class="img-fluid"
            width="90px"
        /></b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto link">
            <b-nav-item href="/"><p>Beranda</p></b-nav-item>
            <b-nav-item href="#"><p>Perusahaan</p></b-nav-item>
            <b-nav-item href="#"><p>Unduh</p></b-nav-item>
            <b-nav-item href="#"><p>Store</p></b-nav-item>
            <b-nav-item href="#"><p>Karir</p></b-nav-item>
            <b-nav-item href="#"><p>Tentang Kami</p></b-nav-item>
            <b-nav-item href="#"><p>Hubungi Kami</p></b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

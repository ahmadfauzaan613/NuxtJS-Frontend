<template>
  <div data-aos="fade-right" class="category container">
    <h1>Category Artikel</h1>
    <div class="row">
      <div class="col-lg-4 col-sm-12 cardcategory">
        <nuxt-link to="/GayaHidup/artikelGayaHidupView">
          <b-card overlay img-src="@/assets/images/1.png" img-alt="Card Image">
            <h3>Gaya Hidup</h3>
          </b-card>
        </nuxt-link>
      </div>
      <div class="col-lg-4 col-sm-12 cardcategory">
        <nuxt-link to="/Diet/artikelDietView">
          <b-card overlay img-src="@/assets/images/2.png" img-alt="Card Image">
            <h3>Diet</h3>
          </b-card>
        </nuxt-link>
      </div>
      <div class="col-lg-4 col-sm-12 cardcategory">
        <nuxt-link to="/Pengasuhan/artikelPengasuhanView">
          <b-card overlay img-src="@/assets/images/3.png" img-alt="Card Image">
            <h3>Pengasuhan</h3>
          </b-card>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide class="slide" img-src="@/assets/images/slide1.png">
        <h5>
          Penyebab kemerahan di sekitar hidung <br />
          dan pengobatan rumahannya
        </h5>
      </b-carousel-slide>
      <b-carousel-slide img-src="@/assets/images/slide2.png">
        <h5>
          Vaksin Moderna Hanya Untuk Booster Nakes dan Masyarakat Yang Belum Di
          Vaksin Covid-19
        </h5>
      </b-carousel-slide>
      <b-carousel-slide img-src="@/assets/images/slide3.png">
        <h5>5 Tips Penting Bagi Para Ibu yang Baru Menyusui</h5>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null,
    }
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true
    },
    onSlideEnd(slide) {
      this.sliding = false
    },
  },
}
</script>

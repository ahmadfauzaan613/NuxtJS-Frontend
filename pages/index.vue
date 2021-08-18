<template>
  <body>
    <Navbar />
    <Homeslide />
    <Category />

    <!-- Artikel -->
    <div data-aos="fade-right" class="container artikel">
      <h1 style="margin-bottom: 30px">Artikel Terbaru</h1>
      <!-- 1 -->
      <div class="cardNewArticle">
        <b-card no-body class="overflow-hidden border-0">
          <b-row no-gutters>
            <b-col lg="4" sm="12">
              <b-card-img
                src="@/assets/images/shutterstock_1987507253-article-1629076660.png"
                alt="Image"
                style="width: 280px"
                class="rounded-0"
              ></b-card-img>
            </b-col>
            <b-col lg="8" sm="12">
              <b-card-text class="text">
                <h1>
                  INI KENAPA COVID-19 VARIAN DELTA <br />
                  LEBIH CEPAT MENGINFEKSI
                </h1>
                <p>
                  Varian delta dikabarkan dapat menginfeksi hanya dengan
                  berpapasan dalam hitungan detik. <br />
                  Transmisi cepat dari varian delta memang benar adanya. Hasil
                  tracing di Australia pada <br />
                  kasus baru menyebutkan bawah penularan virus tidak lagi butuh
                  waktu hingga 15 menit. <br />
                  Namun dimungkinkan bisa hanya dalam hitungan detik.
                </p>
              </b-card-text>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <!-- 1 -->
      <!-- 2 -->
      <div class="cardNewArticle">
        <b-card no-body class="overflow-hidden border-0">
          <b-row no-gutters>
            <b-col lg="4" sm="12">
              <b-card-img
                src="@/assets/images/woman-washing-her-hair-1200x628-facebook-article-1629019358.jpg"
                alt="Image"
                style="width: 280px"
                class="rounded-0"
              ></b-card-img>
            </b-col>
            <b-col lg="8" sm="12">
              <b-card-text class="text">
                <h1>
                  DILARANG KERAMAS USAI MELAHIRKAN, MITOS <br />
                  ATAU FAKTA?
                </h1>
                <p>
                  Di Indonesia banyak mitos yang beredar mengenai kehamilan dan
                  pasca melahirkan. Salah satunya adalah mitos mengenai larangan
                  keramas setelah melahirkan paling tidak sampai 40 hari.
                  Larangan keramas ini juga dikaitkan dengan rambut rontok usai
                  melahirkan.
                </p>
              </b-card-text>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <!-- 2 -->
      <!-- 3 -->
      <div class="cardNewArticle vue">
        <b-card no-body class="overflow-hidden border-0">
          <b-row no-gutters>
            <b-col lg="4" sm="12">
              <b-card-img
                src="@/assets/images/istockphoto-1003089724-612x612-article-1629036193.jpg"
                alt="Image"
                style="width: 280px"
                class="rounded-0"
              ></b-card-img>
            </b-col>
            <b-col lg="8" sm="12">
              <b-card-text class="text">
                <h1>
                  SAYURAN HIJAU DAN TOMAT MEMILIKI <br />
                  MANFAAT BESAR UNTUK CEGAH PENYAKIT <br />
                  JANTUNG
                </h1>
                <p>
                  Para peneliti dari University of Naples meninjau hampir 100
                  studi tentang hubungan antara risiko penyakit jantung dan
                  kebiasaan makan.
                </p>
              </b-card-text>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <!-- 3 -->

      <!-- 4 -->
      <div class="cardNewArticle">
        <b-card no-body class="overflow-hidden border-0">
          <b-row no-gutters>
            <b-col lg="4" sm="12">
              <b-card-img
                src="@/assets/images/106817352-1609332265958-gettyimages-1230350530-hennessy-floridas201229_np1hk-article-1629018870.jpeg"
                alt="Image"
                style="width: 280px"
                class="rounded-0"
              ></b-card-img>
            </b-col>
            <b-col lg="8" sm="12">
              <b-card-text class="text">
                <h1>
                  VAKSIN MODERNA HANYA UNTUK BOOSTER <br />
                  NAKES DAN MASYARAKAT YANG BELUM DI <br />
                  VAKSIN COVID-19
                </h1>
                <p>
                  Pemerintah Indonesia telah menerima hibah vaksin Covid-19
                  Moderna dari Covax Facility sebanyak 8 juta dosis. Vaksin
                  Covid-19 ini sudah mulai diberikan kepada tenaga kesehatan
                  (nakes) dan tenaga penunjang kesehatan sebagai vaksin dosis
                  ketiga.
                </p>
              </b-card-text>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <!-- 4 -->
      <!-- 5 -->
      <div class="cardNewArticle vue">
        <b-card no-body class="overflow-hidden border-0">
          <b-row no-gutters>
            <b-col lg="4" sm="12">
              <b-card-img
                src="@/assets/images/6a07f6d7-892f-484d-9c0c-4d1c9635a2a8-article-1628985366.jpeg"
                alt="Image"
                style="width: 280px"
                class="rounded-0"
              ></b-card-img>
            </b-col>
            <b-col lg="8" sm="12">
              <b-card-text class="text">
                <h1>
                  TANTANGAN IBU MENYUSUI DI MASA <br />
                  PANDEMI
                </h1>
                <p>
                  Saat ini masih banyak masyarakat yang beranggapan bahwa
                  menyusui hanyalah tugas ibu saja, dan seorang ibu pasti bisa
                  menyusui secara alamiah tanpa masalah.
                </p>
              </b-card-text>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <!-- 5 -->
    </div>
    <!-- Artikel -->
    <Footer />
  </body>
</template>

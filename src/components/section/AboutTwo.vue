<template>
  <section>
    <div class="r-container r-center-flex s-mysiloam-text r-ptb-60 r-isWrap element-with-dimensions">
      <div>
        <div class="r-column-3">
          <img
            src="../../assets/bannerLanding-d0c2bbd4.png"
            alt="screenshot_apps"
            class="r-wd-600"
          />
        </div>
      </div>
      <div class="r-column-2 s-mysiloam-body r-justify-text r-ml-auto r-mtb-16">
        <div class="r-isExpand-mobile">
          <img
            src="data:image/png;base64,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"
          />
        </div>
        <div class="r-mt-30">
          <p>
            Lahir melalui komitmen kami untuk terus meningkatkan layanan kami
            kepada Anda, aplikasi ini menawarkan kemudahan dalam menjaga
            kesehatan Anda saat bepergian karena Anda dapat membuat janji dengan
            dokter Anda dalam beberapa klik di mana saja, kapan saja.
          </p>
          <p>
            Untuk lebih meningkatkan pengalaman perawatan kesehatan Anda, kami
            juga memberi Anda informasi tentang rumah sakit kami, membantu Anda
            dalam memfasilitasi pemesanan pemeriksaan kesehatan Anda, akses
            riwayat kesehatan Anda dan memberi Anda tips &amp; artikel kesehatan
            yang diperbarui secara berkala.
          </p>
        </div>
      </div>
    </div>
    <div class="r-container r-center-flex s-mysiloam-text r-ptb-60 r-isWrap element-not-dimensions">
      <div>
        <div class="r-column-3">
          <img
            src="../../assets/bannerLanding-d0c2bbd4.png"
            alt="screenshot_apps"
            class="r-isExpand-mobile"
          />
        </div>
      </div>
      <div class="r-column-2 s-mysiloam-body r-justify-text r-ml-auto r-mtb-16">
        <!---->
        <div class="r-mt-30">
          <p>
            Lahir melalui komitmen kami untuk terus meningkatkan layanan kami
            kepada Anda, aplikasi ini menawarkan kemudahan dalam menjaga
            kesehatan Anda saat bepergian karena Anda dapat membuat janji dengan
            dokter Anda dalam beberapa klik di mana saja, kapan saja.
          </p>
          <p>
            Untuk lebih meningkatkan pengalaman perawatan kesehatan Anda, kami
            juga memberi Anda informasi tentang rumah sakit kami, membantu Anda
            dalam memfasilitasi pemesanan pemeriksaan kesehatan Anda, akses
            riwayat kesehatan Anda dan memberi Anda tips &amp; artikel kesehatan
            yang diperbarui secara berkala.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AboutTwo",
};
</script>

<style lang="css" scoped>
@media screen and (max-width: 800px) {
  .r-isExpand-mobile {
    flex: auto !important;
    max-width: 100% !important;
    width: 100% !important;
  }

  .element-with-dimensions {
    display: none; /* Show the element */
  }

  .element-not-dimensions {
    display: block !important; /* Hide the element */
  }
}

.element-not-dimensions {
    display: none; /* Hide the element */
  }
</style>

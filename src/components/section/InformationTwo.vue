<template>
  <div
    id="bookDoctor"
    class="r-ptb-60 r-container r-center-flex s-mysiloam-text r-isWrap element-with-dimensions"
  >
    <!---->
    <div class="r-column-2 s-mysiloam-body s-txt-right">
      <div>
        <h2>Reservasi Dokter Anda</h2>
        <p>Nikmati kemudahan membuat janji temu dengan dokter via MySiloam.</p>
      </div>
      <div class="r-mt-30">
        <h2>Reservasi Medical Check Up Anda</h2>
        <p>
          Jelajahi paket kami atau ikuti kuesioner 10 menit untuk mengetahui
          paket medical check up mana yang paling cocok untuk Anda.
        </p>
      </div>
    </div>
    <div class="r-column-2 r-ml-auto r-fullCenter-flex">
      <div>
        <img
          src="../../assets/phone_landing_2-2392bae4.png"
          class="r-ht-500 r-mt-30 s-phone-slide"
          alt="mockup_phone"
        />
      </div>
    </div>
  </div>
  <div
    id="bookDoctor"
    class="r-ptb-60 r-container r-center-flex s-mysiloam-text r-isWrap element-not-dimensions"
  >
    <div class="r-fullCenter-flex">
      <div class="r-isExpand-mobile">
        <img
          src="../../assets/phone_landing_2-2392bae4.png"
          class="r-isExpand s-phone-slide"
          alt="mockup_phone"
        />
      </div>
    </div>
    <div class="r-column-2 s-mysiloam-body r-center-text">
      <div>
        <h2>Reservasi Dokter Anda</h2>
        <p>Nikmati kemudahan membuat janji temu dengan dokter via MySiloam.</p>
      </div>
      <div class="r-mt-30">
        <h2>Reservasi Medical Check Up Anda</h2>
        <p>
          Jelajahi paket kami atau ikuti kuesioner 10 menit untuk mengetahui
          paket medical check up mana yang paling cocok untuk Anda.
        </p>
      </div>
    </div>
    <!---->
  </div>
</template>

<script>
export default {
  name: "InformationTwoComponent",
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

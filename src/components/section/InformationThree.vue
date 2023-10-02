<template>
  <div class="r-page-background-2-bg">
    <div
      id="patientPortal"
      class="r-ptb-60 r-container r-center-flex s-mysiloam-text r-isWrap element-with-dimensions"
    >
      <div class="r-column-2 r-fullCenter-flex">
        <div class="s-mysiloam-body">
          <!----><img
            src="../../assets/phone_landing_4-da158707.png"
            class="r-ht-500 s-phone-slide"
            alt="mockup_phone"
          />
        </div>
      </div>
      <div class="r-column s-mysiloam-body">
        <div class="r-text-left">
          <h2>Akses data kesehatan Anda dimana saja, kapan saja</h2>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-16 r-ht-80 r-center-flex"
          >
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mr-16"
            >
              <img
                src="../../assets/healthTracker_icon-26a243cd.svg"
                alt="health tracker"
                class="r-ht-40"
              />
            </div>
            <p>Cek hasil laboratorium dan radiologi Anda</p>
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-16 r-ht-80 r-center-flex"
          >
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mr-16"
            >
              <img
                src="../../assets/drugs_icon-d2cc019d.svg"
                alt="drug"
                class="r-ht-40"
              />
            </div>
            <p>Akses riwayat pembelian obat</p>
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-16 r-ht-80 r-center-flex"
          >
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mr-16"
            >
              <img
                src="../../assets/invoice_icon-0371220d.svg"
                alt="invoice"
                class="r-ht-40"
              />
            </div>
            <p class="r-text-left">
              Monitor proses pemulangan dan jumlah tagihan berjalan selama
              dirawat inap
            </p>
          </div>
        </div>
      </div>
    </div>
    <div
      id="patientPortal"
      class="r-ptb-60 r-container r-center-flex s-mysiloam-text r-isWrap element-not-dimensions"
    >
      <div class="r-column-2 r-fullCenter-flex">
        <div class="s-mysiloam-body">
          <div class="r-center-text">
            <h2>Akses data kesehatan Anda dimana saja, kapan saja</h2>
          </div>
          <img
            src="../../assets/phone_landing_4-da158707.png"
            class="r-isExpand-mobile s-phone-slide"
            alt="mockup_phone"
          />
        </div>
      </div>
      <div class="r-column s-mysiloam-body">
        <!---->
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-16 r-center-text r-ptb-16"
          >
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mtb-16"
            >
              <img
                src="../../assets/healthTracker_icon-26a243cd.svg"
                alt="health tracker"
                class="r-ht-40"
              />
            </div>
            <p>Cek hasil laboratorium dan radiologi Anda</p>
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-16 r-center-text r-ptb-16"
          >
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mtb-16"
            >
              <img
                src="../../assets/drugs_icon-d2cc019d.svg"
                alt="drug"
                class="r-ht-40"
              />
            </div>
            <p>Akses riwayat pembelian obat</p>
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-16 r-center-text r-ptb-16"
          >
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mtb-16"
            >
              <img
                src="../../assets/invoice_icon-0371220d.svg"
                alt="invoice"
                class="r-ht-40"
              />
            </div>
            <p>
              Monitor proses pemulangan dan jumlah tagihan berjalan selama
              dirawat inap
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InformationThreeComponent",
};
</script>

<style lang="css" scoped>
.r-page-background-2-bg,
.s-banner-page-background-2-bg {
  background: #f9f9f9 !important;
}

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

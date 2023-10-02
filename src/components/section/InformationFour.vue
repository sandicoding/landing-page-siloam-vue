<template>
  <div class="s-mysiloam-bg element-with-dimensions">
    <div
      id="covidTesting"
      class="r-ptb-60 r-container r-center-flex s-mysiloam-text r-isWrap"
    >
      <!---->
      <div class="r-column-2 s-mysiloam-body">
        <div class="s-txt-right">
          <h2>Pesan Test COVID-19 hanya dengan beberapa klik</h2>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-20 r-ht-80 r-center-flex s-txt-right"
          >
            <p class="r-isExpand">Pilih tes yang Anda perlukan</p>
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-ml-16"
            >
              <img
                src="../../assets/tap_icon-c0120818.svg"
                alt="tap"
                class="r-ht-50"
              />
            </div>
            <!---->
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-20 r-ht-80 r-center-flex s-txt-right"
          >
            <p class="r-isExpand">Isi detail dan lengkapi proses</p>
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-ml-16"
            >
              <img
                src="../../assets/clipboard_icon-be944002.svg"
                alt="clipboard"
                class="r-ht-50"
              />
            </div>
            <!---->
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-white-bg r-isExpand s-mysiloam-body r-plr-20 r-ht-80 r-center-flex s-txt-right"
          >
            <p class="r-isExpand">Anda siap untuk melakukan tes</p>
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-ml-16"
            >
              <img
                src="../../assets/check_icon-d1fa53cb.svg"
                alt="check"
                class="r-ht-50"
              />
            </div>
            <!---->
          </div>
        </div>
      </div>
      <div class="r-column-2 r-fullCenter-flex">
        <div>
          <img
            src="../../assets/phone_landing_5-defa025a.png"
            class="r-ht-500 r-mt-30 s-phone-slide"
            alt="mockup_phone"
          />
        </div>
      </div>
    </div>
  </div>
  <div class="s-mysiloam-bg-phone element-not-dimensions">
    <div
      id="covidTesting"
      class="r-ptb-60 r-container r-center-flex s-mysiloam-text r-isWrap"
    >
      <div class="r-column-2 r-fullCenter-flex">
        <div class="s-mysiloam-body">
          <div class="r-center-text">
            <h2>Pesan Test COVID-19 hanya dengan beberapa klik</h2>
          </div>
          <img
            src="../../assets/phone_landing_5-defa025a.png"
            class="r-isExpand-mobile s-phone-slide"
            alt="mockup_phone"
          />
        </div>
      </div>
      <div class="r-column-2 s-mysiloam-body">
        <!---->
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-20 r-center-text r-ptb-16"
          >
            <!---->
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mtb-16"
            >
              <img
                src="../../assets/tap_icon-c0120818.svg"
                alt="tap"
                class="r-ht-50"
              />
            </div>
            <p class="r-isExpand">Pilih tes yang Anda perlukan</p>
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-isExpand r-white-bg s-mysiloam-body r-plr-20 r-center-text r-ptb-16"
          >
            <!---->
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mtb-16"
            >
              <img
                src="../../assets/clipboard_icon-be944002.svg"
                alt="clipboard"
                class="r-ht-50"
              />
            </div>
            <p class="r-isExpand">Isi detail dan lengkapi proses</p>
          </div>
        </div>
        <div class="r-mt-30 r-fullCenter-flex">
          <div
            class="s-mysiloam-card r-white-bg r-isExpand s-mysiloam-body r-plr-20 r-center-text r-ptb-16"
          >
            <!---->
            <div
              class="r-fullCenter-flex r-square-60 r-isExpand-mobile r-mtb-16"
            >
              <img
                src="../../assets/check_icon-d1fa53cb.svg"
                alt="check"
                class="r-ht-50"
              />
            </div>
            <p class="r-isExpand">Anda siap untuk melakukan tes</p>
          </div>
        </div>
      </div>
      <!---->
    </div>
  </div>
</template>

<script>
export default {
  name: "InformationFour",
};
</script>

<style lang="css" scoped>
.s-mysiloam-bg,
.s-mysiloam-bg-phone {
  background-repeat: no-repeat;
  background-size: cover;
}
.s-mysiloam-bg {
  background-image: url(../../assets/mysiloam_bg_3-5c7d3224.png);
  background-position: bottom;
}

.s-mysiloam-bg-phone {
  background-image: url(../../assets/mysiloam_bg_3-5c7d3224.png);
  background-position: 100%;
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

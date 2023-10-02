<template>
  <div
    class="r-container s-mysiloam-footer-bg r-fullCenter-flex s-mysiloam-text"
  >
    <div class="s-mysiloam-body">
      <div class="r-fullCenter-flex">
        <img
          src="data:image/png;base64,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"
          alt="logo mysiloam"
          class="r-wd-150"
        />
      </div>
      <div class="r-center-text r-white-text r-mt-30">
        <h2>"Save Your Time, Improve Your Life"</h2>
        <p class="r-mt-16">Klik link untuk mengunduh aplikasi</p>
        <div class="r-fullCenter-flex r-mt-10">
          <a
            href="https://play.google.com/store/apps/details?id=com.siloam.android"
            target="_blank"
            ><img
              src="../../assets/gPlay-466586a2.png"
              class="r-wd-150 r-isClickAble s-phone}"
              alt="windows" /></a
          ><a href="https://apps.apple.com/id/app/id1456325611" target="_blank"
            ><img
              src="data:image/png;base64,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"
              class="r-wd-150 r-ml-16 r-isClickAble s-phone}"
              alt="ios"
          /></a>
        </div>
      </div>
    </div>
  </div>
  <div class="r-container r-ptb-20">
    <a href="/privacy-policy" class=""
      ><p class="r-center-text r-600 s-txt-link">Privacy &amp; Policy</p></a
    >
    <hr class="r-line-1" />
  </div>
</template>

<script>
export default {
  name: "InformationDownload",
};
</script>

<style lang="css" scoped>
.s-mysiloam-footer-bg {
  background: linear-gradient(
      135deg,
      rgba(0, 57, 121, 0.5),
      rgba(0, 57, 121, 0.5)
    ),
    url(../../assets/mysiloam_bg_2-c50df1b2.png);
  background-position: 50%;
  background-repeat: no-repeat;
  background-size: cover;
  height: 75vh;
  max-height: 720px;
  overflow: hidden;
  position: relative;
}
</style>

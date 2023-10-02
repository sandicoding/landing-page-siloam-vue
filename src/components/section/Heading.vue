<template>
  <main class="r-main">
    <section>
      <div
        id="landingMain"
        class="r-container r-center-flex s-mysiloam-lannding-bg r-wrap-flex element-with-dimensions"
      >
        <div class="s-mysiloam-rectangle"></div>
        <div class="s-mysiloam-text r-column-2">
          <div>
            <img
              src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQMAAAA5CAMAAAAFmb6GAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAACHUExURUdwTHJ1nyswcIKuapymtWBikSUrbN3g5bG6vmeeTTxAfCswcElPhDI4dCwycV1jkR4jZ2KbRR8laCAnaURJgWGZRHipX2xwnERJgSctbXyrZTc8eG2iVISxbmyhUaXEmIOwbkFFfjA1c2Zql0BEfiUqa3SmW0ZLgkdMg5/EjxwiZmOaRmGaRbE+onoAAAAqdFJOUwAx1jURfPEHIPGe4U88rRz8u+P2hd2kR5TphsfTbeU2V6zRXrbDwWFyYfuL1RwAAAipSURBVGje7ZqJdqM2FEARVhAYjBlDDN53mzH8//dVC1qRsJP4dNJmXnvOEBZhXd4ued5f+Sv/hsApmGABU/R9f+NvIaH1eiiu7z4x/1Pqx0Ge5cHCv4xLnQOaAgDpGQQ7+UOc3lsuS+v1ubj+66NDgyq+37O7FL9QOKMCXz3W5PDt3MnpTzPYWtVg/VkG0+rel6CAHMGZnsjG+HjML7/9IQYNl9am7HtxufkYg/KY3W2ymrLrp+7vDHwrBkurKXyOwcS/O6SDkPK/q2/FYA37phB9Tg9gfHfKmbwGCQYp+k4MLMagmMJHGMDDfUAKjcH30oOmbwzzzzEAuZxx7l8uF3+hMIgB8Qedu8i/iz9gRt9uTUWA0ecYjCWBNAlx1A/LSlLIbkQR2D1Z5X0rBk2zN02h/RQDKB1iIdIeIF3EWckP0LdhEF3pP1djLiwqXKP2YwzkdOOpPJtwA8nybnjQZdAuBgiGWKD7RSgMARi8A6tgCEIt/6SPIAuDPdGF9j00ogI5GS0FAzRiYn53dlZ+8kCLAfwHS+3Ar5kmEyrJxMEAJsXF92Mfu5MimVqUbVKPyQ3kjrRIgDzPRibPoEmNfVGM83Q+AqhT9kiVQJMBnW4TbbTXbFrC4LoXDOB6S0VHhebG2YlgcFQ/UaUyeBuOjajGOVbnNvHB8WSUEvC0ytVYk/l1d0cSiMHCsfgh2YpAQjf/LtL3MzAYdMmQZgzoF2WwGUlbWNqyqbAxngULiz/AoWDF5REDlPRSLL9WX3la9ENufDIYSHWk3vnkwbP2QF4bDFgmEKlfeLRt8eyiUGHADtt12EsisDlZMqQsX0mdE+UhqQ+HGKAi6E8xHwuDgEVuyzuCk8ZgZeRpWTk2HstPOoNwSyGoxrBp2OdVGMA1PYz2mik0Bhd0UX/ZpSotzYMhBvYpZmPE7SS3J18zqDLoSV93YqgxYOlQe1UM+EpyR0xFYYBdBL1trhaIUe/Um/Hr41VVwqcZJI45ZEXP1AypBxlYpNIZ7NiB9Pm7iDDAoUJl0KmLagwMS6MGi6mlYsqOY8UVDzBwTzFPDN9698/jw0oWqCv4QQY+1BjAK60ZlvrcyOdVGaA58RGtkk1hz2lS8byb7TPe8/gNPGSAlCRzdQKgrKRdr3RvE5ymECFYCuI+0BlgO6wuGlLjTAY0BmhJgoBSPF7bztOpDHDqiO2jVTR/FNE8U4+qqHKAn3HP5mQg1SC4MQcAjuLxUi1GhF8vhcXrDI4AD4DKwChVEFhpA0oG3o4yEMYQ0sBIgr7GAEWUQQMNUwjNyjFzUDiWwwwKraww8k7iFm98ZJ+/EwlqE5VB0F2vMjMQgLtmfZKBd9V825Kbgs4AnydshDGgNTWha8/xJ64uSlAPMUAzTfEN01pgLbotAiapSFDsDKpe2nrk8enoYsBiYcTug2ua+ex6DLq/5lB6zqY1TIGN8HYM3K7NxUD+4JviY2MR40m3mgsvGngvItMY5CVHNOvloWcXg11EPzEroHeN8A46A9SlCKGSRLRba2Me3g4LWygnlZSLgdD0ACgDnW0VBcI0wKlIpbvQGMyEqQgGCX/04GKAvSBhsETcFLoooTPgKcJGJBFEK5xldFmsclsnycWg1hIeLsJJCP1HZT0+H3OteZ89YjB5zGDP3OC0SwhxBAgtDEgKTbIpiqpzpPuh6hWVY4MDNmsXAzHbmTXWXrp64pyrQfdJPcieYBAyNd/zebdrz8IApwgU1Uiqyxo+WmyYFBcVQ+lkUImUSquRBANCvkzVsbIse1IPnmGAWPE4F95/aWPQqQu9SJ2DuUQFik5q1UvAeqEawyMGdzeDJO5lX6/Tg653th6RqEDO7qwMusJpjbi6RHpTRbi1RamzkdHy8JhB7LKF6cwohc68zHyFHrCpk5xvr3o6kwFLHRoy82UjXYOlaXbTLUJm0OkT/sDlEwsl3xrXJZhCL36hHiA+p7maB/UY7Nquk8KYtUZyUPayFDOnHWBw4wADRYnQWYkowqTimncU8hfqAS8ed9tWCfo9Bh6b+rq7EhkeMexlq6ZVYzguBuLhTGkcTRfSmYqkUCZR8JX+AM+OFgMsUZh7LgYb2oFtd0tSQja9PFnYfZaqeKZibSk7uesF8XCM+qbgT6Uy+UDE3vsr9aAz9ZYy2DsZMD1p5zRT6CcH0mKzVGo0SLMn8gPlYbFOLwNBhaQySQbpa/VgtO3WHptmC50MWAe2jdrWmierzcxZegIkt1cXmu4H5GYwFalvXkHWQo7Vcr80OirYxPLXMkDXbt2plfmvhcGeL1G21iV7o3uQLQK9kgZDfSTF78dpUaRKn4gsUO1kE6gk1hIWEm7+EgZ8eQ1/4d0Ag/AqluCikSUtPD7s4rkZwJWzKUriAFL0KTjqzePMwSD7GANWDZD81xtgQBKDlq1TWvNkd0+QRPXpcE8VBM+2E5U8WRSGL9CDbrGlVYK+jUEo9GBj34rj3ISRXcCj3npifTjnrbVAQWDcc3uJHni/20bJk10MaLeRrdI59iO5NLpb4hpcZ7IRFC7Qqwat7BV64G3NJWgrgw1bYDPzZCW3u9l2ZR1vT6yxYJ9QGcYUjBXWlV6JZ2mdyV75J/RgOSei+vYNPaNsxwjnv4gYi4zvjMHvgW0IZeqrpp3HaSnWy05+JzjkF/z4pG5u9GXIO1b6SlV5kYupeFAE/LiTBCtgN9hKMLjwq4JBxd/4pR0PO7ZFJRrsHKAwqcfnlT/zV+dDnair/nRrARWyRUAeK5STujqcD+OiLnsvgUlxPpJRqxvtnwMuIdmTYA4mrkK5KaET+BUGLKFsll8YAtH/XySI/qcMPXBV3vO196/pMkO0836u7BrK4Ip+LoKQ9hT7m7h+yOx32O3sui286/BHMthE7+/vUfN1j/hfZqDsWPyp3mDTMk/Q2ivGn8OALaz8VATevmFr7+tl+FMReHC032w2+9H/h8A/pftC6AI6V4kAAAAASUVORK5CYII="
            />
          </div>
          <div class="s-mysiloam-body r-mt-16 r-wd-500">
            <p>Dibuat oleh Siloam Hospitals, untuk</p>
            <div class="s-mysiloam-title">
              <h2>Mempermudah Perjalanan</h2>
              <h2>Kesehatan Anda</h2>
            </div>
          </div>
          <div class="s-mysiloam-body r-mt-30">
            <p>Klik link untuk mengunduh aplikasi</p>
            <div class="r-center-flex r-mt-10">
              <a
                href="https://play.google.com/store/apps/details?id=com.siloam.android"
                target="_blank"
                ><img
                  src="../../assets/gPlay-466586a2.png"
                  class="r-wd-150 r-isClickAble s-phone-slide"
                  alt="windows" /></a
              ><a
                href="https://apps.apple.com/id/app/id1456325611"
                target="_blank"
                ><img
                  src="data:image/png;base64,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"
                  class="r-wd-150 r-ml-16 r-isClickAble s-phone-slide"
                  alt="ios"
              /></a>
            </div>
          </div>
        </div>
        <div class="r-column-2 r-ml-auto r-fullCenter-flex">
          <div>
            <img
              src="../../assets/phone_landing-87f4f1ca.png"
              class="r-wd-400 r-mt-30 s-phone-slide"
              alt="mockup_phone"
            />
          </div>
        </div>
      </div>
      <div
        id="landingMain"
        class="r-center-flex r-isWrap element-not-dimensions"
      >
        <div class="s-mysiloam-landing-bg-mobile">
          <div class="s-mysiloam-rectangle-mobile"></div>
          <div class="r-fullCenter-flex">
            <div>
              <img
                src="../../assets/phone_landing-87f4f1ca.png"
                class="r-wd-350 s-phone-slide s-phone-landing s-phone-slide"
                alt="mockup_phone"
              />
            </div>
          </div>
        </div>
        <div class="r-container s-mysiloam-text r-mtb-16 r-isWrap r-isExpand">
          <div class="r-isExpand-mobile r-fullCenter-flex">
            <img
              src="data:image/png;base64,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"
            />
          </div>
          <div class="s-mysiloam-body r-center-text r-mt-16">
            <p>Dibuat oleh Siloam Hospitals, untuk</p>
            <div class="s-mysiloam-title">
              <h2>Mempermudah Perjalanan</h2>
              <h2>Kesehatan Anda</h2>
            </div>
          </div>
          <div class="s-mysiloam-body r-mt-30 r-center-text">
            <p>Klik link untuk mengunduh aplikasi</p>
            <div class="r-fullCenter-flex r-mt-10">
              <a
                href="https://play.google.com/store/apps/details?id=com.siloam.android"
                target="_blank"
                ><img
                  src="../../assets/gPlay-466586a2.png"
                  class="r-wd-150 r-isClickAble"
                  alt="windows" /></a
              ><a
                href="https://apps.apple.com/id/app/id1456325611"
                target="_blank"
                ><img
                  src="data:image/png;base64,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"
                  class="r-wd-150 r-ml-16 r-isClickAble"
                  alt="ios"
              /></a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>

export default {
  name: "HeadingSection",
  computed: {
    isSmallScreen() {
      return window.innerWidth < 800;
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.s-phone-slide {
  animation-duration: 1s;
  -webkit-animation-duration: 1s;
  animation-name: slideUp;
  -webkit-animation-name: slideUp;
  visibility: visible;
}

@keyframes slideUp {
  0% {
    opacity: 0;
    -webkit-transform: translateY(70%);
  }

  to {
    opacity: 1;
    -webkit-transform: translateY(0);
  }
}

a {
  text-decoration: none !important;
}

.s-mysiloam-text .s-mysiloam-body h2 {
  font-size: 32px;
}

.s-mysiloam-text .s-mysiloam-body p {
  color: #33333380;
  font-size: 16px;
  line-height: 25px;
}

.s-mysiloam-text .s-mysiloam-body h1,
.s-mysiloam-text .s-mysiloam-body h2,
.s-mysiloam-text .s-mysiloam-body h3 {
  color: #1c2674;
  font-weight: 700;
  line-height: 40px;
}

.s-mysiloam-text {
  z-index: 20;
}

.s-mysiloam-lannding-bg {
  background-image: url(../../assets/head-bg.png);
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
  max-height: 720px;
  overflow: hidden;
  text-align: left;
  position: relative;
}

.s-mysiloam-rectangle {
  background: #fff;
  border-radius: 50px;
  position: absolute;
  top: 0;
  transform: rotate(-45deg);
  height: 873.08px;
  left: -650px;
  width: 1159.14px;
}
.s-mysiloam-rectangle-mobile {
  height: 700px;
  left: -850px;
  width: 1000px;
  z-index: 0;
}
.s-mysiloam-rectangle,
.s-mysiloam-rectangle-mobile {
  background: #fff;
  border-radius: 50px;
  position: absolute;
  top: 0;
  transform: rotate(-45deg);
}

.s-phone-landing {
  position: relative;
  z-index: 500;
}

.s-mysiloam-landing-bg-mobile {
  background: linear-gradient(
      -45deg,
      rgba(111, 147, 223, 0.781),
      hsla(0, 0%, 100%, 0.411)
    ),
    url(../../assets/head-bg.png);
  background-repeat: no-repeat;
  background-size: cover;
  height: -moz-fit-content;
  height: fit-content;
  position: relative;
  width: 100%;
}

.show-on-desktop {
  display: block;
}

@media screen and (max-width: 800px) {
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

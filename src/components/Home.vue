<template>
  <section>
    <Heading />
    <About />
    <FeatureApp />
    <AboutTwo />
    <Information/>
  </section>
</template>

<script>
import About from "./section/About.vue";
import Heading from "./section/Heading.vue";
import FeatureApp from "./section/FeatureApp.vue";
import AboutTwo from "./section/AboutTwo.vue";
import Information from "./section/Information.vue";

export default {
  name: "HomePage",
  components: { Heading, About, FeatureApp, AboutTwo, Information },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>

<template>
  <section>
    <Heading />
    <About />
    <FeatureApp />
    <AboutTwo />
    <Information />
    <InformationTow />
    <InformationThree />
    <InformationFour />
    <HospitalList />  
    <InformationDownload />
    <InformationMitra />
  </section>
</template>

<script>
import About from "./section/About.vue";
import Heading from "./section/Heading.vue";
import FeatureApp from "./section/FeatureApp.vue";
import AboutTwo from "./section/AboutTwo.vue";
import Information from "./section/Information.vue";
import InformationTow from "./section/InformationTwo.vue";
import InformationThree from "./section/InformationThree.vue";
import InformationFour from "./section/InformationFour.vue";
import HospitalList from "./section/HospitalList.vue";
import InformationDownload from "./section/InformationDownload.vue";
import InformationMitra from "./section/InformationMitra.vue";

export default {
  name: "HomePage",
  components: {
    Heading,
    About,
    FeatureApp,
    AboutTwo,
    Information,
    InformationTow,
    InformationThree,
    InformationFour,
    HospitalList,
    InformationDownload,
    InformationMitra,
},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

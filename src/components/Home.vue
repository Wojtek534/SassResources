<template>
  <section class="section-home">
    <feature-box/>
    <flipper-card/>
  </section>
</template>
<script>
import FeatureBox from "../components/content/featureBox/FeatureBox";
import FlipperCard from "../components/content/flipperCard/FlipperCard";
export default {
  components: {
    FeatureBox,
    FlipperCard
  }
};
</script>

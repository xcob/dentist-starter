<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
<LandingHeroContainer>
  <LandingHero></LandingHero>
</LandingHeroContainer>
  <LandingContainer>
    <LandingFeatures></LandingFeatures>
    <LandingTextWithImage></LandingTextWithImage>
    <LandingTextWithImageReverse></LandingTextWithImageReverse>
    <LandingCta></LandingCta>
  </LandingContainer>
</template>

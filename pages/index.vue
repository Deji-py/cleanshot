<template>
  <main class="flex flex-col justify-center items-center">
    <Header />
    <HeroSection />
    <ProductTab />
    <Features />
    <QuickAccess />
    <Annotate />
    <ClientShot_Cloud />
    <ScrollingCapture />
    <ScreenRecorder />
    <BackgroundTool />
    <TextRecognition />
    <PinScreenShot />
    <HideIcons />
    <Features_2 />
    <Feedback />
    <CtaSection />
    <NewsLetter />
    <Footer />
  </main>
</template>

<style>
:root {
  --primary: #0669ff;
}

.text-primary {
  color: var(--primary);
}

.bg-primary {
  background-color: var(--primary);
}

body {
  font-family: "Inter", sans-serif;
}
</style>
<script>
import Footer from "../components/Footer.vue";
import Features_2 from "../components/Features_2.vue";
import PinScreenShot from "../components/PinScreenShot.vue";
import TextRecognition from "../components/TextRecognition.vue";
import BackgroundTool from "../components/BackgroundTool.vue";
import ScreenRecorder from "../components/ScreenRecorder.vue";
import ScrollingCapture from "../components/ScrollingCapture.vue";
import ClientShot_Cloud from "../components/ClientShot_Cloud.vue";
import Features from "../components/Features.vue";
import QuickAccess from "../components/QuickAccess.vue";
import Header from "../components/Header.vue";
import HeroSection from "../components/HeroSection.vue";
import ProductTab from "../components/ProductTab.vue";
import Annotate from "../components/Annotate.vue";
import HideIcons from "../components/HideIcons.vue";
import Feedback from "../components/Feedback.vue";
import CtaSection from "../components/CtaSection.vue";
import NewsLetter from "../components/Newsletter.vue";
export default {
  name: "IndexPage",
  components: {
    Features,
    QuickAccess,
    HeroSection,
    Header,
    ProductTab,
    Annotate,
    ClientShot_Cloud,
    ScrollingCapture,
    ScreenRecorder,
    BackgroundTool,
    TextRecognition,
    PinScreenShot,
    HideIcons,
    Features_2,
    Feedback,
    CtaSection,
    NewsLetter,
    Footer,
  },
};
</script>

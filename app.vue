<script setup>
useHead({
  title:
    "Frontend Mentor | Fylo landing page with dark theme and features grid",
  link: [
    {
      rel: "icon",
      type: "image/png",
      sizes: "32x32",
      href: "/images/favicon-32x32.png",
    },
  ],
  link: [
    {
      rel: "stylesheet",
      href: "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css",
    },
  ],
});
</script>
<template>
  <div>
    <Header />
    <HeroSection />
    <div class="bg-navy-900 md:px-[7rem]">
      <FeatureSection />
      <ProductiveSection />
      <TestimonialSection />
      <NewsLetterSection />
    </div>
    <Footer />
  </div>
</template>

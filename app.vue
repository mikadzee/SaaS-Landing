<template>
  <Header />
  <main>
    <CTA />
    <Partners />
    <Product />
    <Features />
    <Testimonials />
    <Questions />
  </main>

  <Footer />
</template>

<script setup>
  useHead({
    title: 'SaaS Landing Page',
    meta: [
      { name: 'description', content: 'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com' }
    ]
  })
</script>
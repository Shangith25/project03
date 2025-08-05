<template>
  <q-page class="q-pa-md">
    <!-- Hero Section -->
    <div class="q-pa-xl bg-primary text-white text-center">
      <h1 class="text-h2 q-mb-md">Welcome to Our Website</h1>
      <p class="text-subtitle1">Empowering your ideas with modern web solutions</p>
      <q-btn color="white" text-color="primary" label="Get Started" class="q-mt-md" />
    </div>

    <!-- Description Section -->
    <div class="q-my-xl text-center">
      <h2 class="text-h4 q-mb-sm">Why Choose Us?</h2>
      <p class="text-subtitle2 q-mx-auto" style="max-width: 600px;">
        We offer the best in design, performance, and customer service. Our team is dedicated to building modern, scalable applications that make your business stand out.
      </p>
    </div>

    <!-- Cards Section -->
    <div class="row q-col-gutter-md q-mb-xl">
      <q-card class="col-xs-12 col-sm-6 col-md-4">
        <q-card-section>
          <div class="text-h6">Fast Performance</div>
          <div class="text-subtitle2">Built for speed and scalability</div>
        </q-card-section>
        <q-card-section>
          <q-icon name="speed" size="48px" color="primary" />
        </q-card-section>
      </q-card>

      <q-card class="col-xs-12 col-sm-6 col-md-4">
        <q-card-section>
          <div class="text-h6">Modern Design</div>
          <div class="text-subtitle2">Clean, professional interfaces</div>
        </q-card-section>
        <q-card-section>
          <q-icon name="brush" size="48px" color="primary" />
        </q-card-section>
      </q-card>

      <q-card class="col-xs-12 col-sm-6 col-md-4">
        <q-card-section>
          <div class="text-h6">24/7 Support</div>
          <div class="text-subtitle2">We're always here to help</div>
        </q-card-section>
        <q-card-section>
          <q-icon name="support_agent" size="48px" color="primary" />
        </q-card-section>
      </q-card>
    </div>
  </q-page>
</template>

<script setup>
// No special logic needed for this static homepage
</script>

<style scoped>
/* Optional: customize styling */
</style>

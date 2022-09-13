<script setup>
import NavbarComponent from '@/components/NavbarComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>

<template>
  <NavbarComponent />
  <div>
    <main>
      <RouterView />
    </main>
  </div>
  <FooterComponent />
</template>

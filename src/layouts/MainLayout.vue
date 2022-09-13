<script>
import NavbarComponent from '@/components/NavbarComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';

export default {
  name: 'MainLayout',
  components: {
    NavbarComponent,
    FooterComponent,
  },
};
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

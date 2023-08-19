<script>
import AppSidebar from './components/AppSidebar.vue';
import AppChatSection from './components/AppChatSection.vue';

export default {
  components: { AppSidebar, AppChatSection },
}
</script>

<template>
  <!--Main content:-->

  <main class="container shadow bg-white">

    <div class="row h-100">

      <!-- SIDEBAR SECTION -->
      <AppSidebar />

      <!-- CHAT SECTION -->
      <AppChatSection />

    </div>

  </main>
</template>

<style lang="scss">
@use './assets/scss/style.scss'
</style>

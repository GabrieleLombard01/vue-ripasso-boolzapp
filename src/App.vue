<script>
import AppSidebar from './components/AppSidebar.vue';
import AppChatSection from '';

export default {
  components: { AppSidebar },
}
</script>

<template>
  <div class="h-100 d-flex align-items-center justify-content-center">

    <!--Main content:-->
    <main class="container">

      <!-- SIDEBAR SECTION -->
      <AppSidebar />

      <!-- CHAT SECTION -->

    </main>

  </div>
</template>

<style lang="scss">
@use './assets/scss/style.scss'
</style>

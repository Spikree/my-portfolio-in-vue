<script setup>
  import Header from './components/header.vue';
  import one from './components/one.vue';
  import About from './components/aboutMe.vue';
</script>

<template>
  <div>
    <section>
      <Header />
      <one />
    </section>

    <section>
      <About/>
    </section>
   
  </div>
</template>

<style scoped>
  section {
    height: 100vh;
  }
</style>

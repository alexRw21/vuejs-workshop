<script setup>
import Header from "./components/Header.vue";
</script>

<template>
  <div class="bg-slate-50 flex flex-col min-h-screen">
    <Header />
    <main class="container mx-auto m-8 border-2 border-dashed rounded p-8">
      <RouterView />
    </main>
  </div>
</template>

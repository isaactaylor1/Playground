<template>
  <app-layout title="RandomFacts">
    <template #header>
      <h2 class="font-semibold text-xl text-gray-800 leading-tight">
        Random Facts
      </h2>
    </template>

    <div class="py-12">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div
          class="
            bg-white bg-white
            overflow-hidden
            shadow-xl
            sm:rounded-lg
            rounded
            shadow
            p-6
          "
        ></div>
      </div>
    </div>
  </app-layout>
</template>
<script>
import AppLayout from "@/Layouts/AppLayout.vue";

export default {
  components: {
    AppLayout,
  },
};
</script>
<style scoped>
.completed {
  text-decoration: line-through;
}
</style>

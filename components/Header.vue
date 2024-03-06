<template>
  <div>
    <div class="headers bg-alianza-800 pt-[92px]">
      <h1
        class="flex h-[250px] items-center justify-center pb-8 pt-4 font-chakra text-4xl font-bold uppercase text-gray-100 md:pb-16 md:pt-8 md:text-7xl lg:pb-16 lg:pt-8 lg:text-7xl"
      >
        {{ titulo }}
      </h1>
    </div>
  </div>
</template>

<script setup>
defineProps({
  titulo: String,
});
</script>

<style>
.headers {
  background-image: url(~/assets/img/grid.svg);
}
</style>

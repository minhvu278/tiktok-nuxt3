<template>
  <top-nav></top-nav>
  <div
      :class="route.fullPath === '/' ? 'max-w-[1140px]': ''"
      class="flex justify-between mx-auto w-full lg:px-2.5 px-0"
  >
    <div>
      <side-nav-main></side-nav-main>
    </div>

    <slot />
  </div>
</template>

<script setup>
  import {useRoute} from "vue-router";

  const route = useRoute()
</script>

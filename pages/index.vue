<template>
  <main-layout>
    <div class="pt-[80px] w-[calc(100%-90px)] max-w-[690px]">
      <post-main></post-main>
    </div>
  </main-layout>
</template>

<script>
import MainLayout from "~/layouts/MainLayout.vue";
import PostMain from "~/components/PostMain.vue";

export default {
  components: {PostMain, MainLayout}

}
</script>
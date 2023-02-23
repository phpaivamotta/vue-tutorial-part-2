<script setup>
import { useFlash } from "@/composables/useFlash";

let { flash } = useFlash();
</script>

<template>
  <main>
    <button type="button" @click="flash('WHY?!WHYYYYY!! On about page.')">
      Click Me
    </button>
  </main>
</template>

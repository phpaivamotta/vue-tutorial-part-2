<script setup>
import { useFlash } from "@/composables/useFlash";

let { flash } = useFlash();
</script>

<template>
  <main>
    <button
      type="button"
      @click="flash('Please stop clicking me, it hurts so bad!')"
    >
      Click Me
    </button>
  </main>
</template>

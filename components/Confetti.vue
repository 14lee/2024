<template>
  <div class="relative flex h-24 w-full flex-col items-center justify-center">
    <button
      class="rounded-lg bg-foreground px-4 py-2 text-background transition duration-500 hover:scale-110"
    >
    </button>
  </div>
</template>

<script setup lang="ts">
import { useSlideContext } from '@slidev/client'
import { watch } from 'vue'
import confetti from "canvas-confetti";

const slideContext = useSlideContext()

watch(() => slideContext.$nav.value.currentPage, () => {
  if(slideContext.$nav.value.currentPage === slideContext.$page.value) {
    handleClick()
  }
})

// Function to trigger the confetti side cannons
function handleClick() {
  const end = Date.now() + 3 * 100; // 3 seconds
  const colors = ["#a786ff", "#fd8bbc", "#eca184", "#f8deb1"];

  // Frame function to trigger confetti cannons
  function frame() {
    if (Date.now() > end) return;

    // Left side confetti cannon
    confetti({
      particleCount: 2,
      angle: 60,
      spread: 55,
      startVelocity: 60,
      origin: { x: 0, y: 0.5 },
      colors: colors,
    });

    // Right side confetti cannon
    confetti({
      particleCount: 2,
      angle: 120,
      spread: 55,
      startVelocity: 60,
      origin: { x: 1, y: 0.5 },
      colors: colors,
    });

    requestAnimationFrame(frame); // Keep calling the frame function
  }

  frame();
}
</script>

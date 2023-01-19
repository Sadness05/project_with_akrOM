<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
     <aside class="max-w-[257px] relative">
      <div class="flex gap-2 px-16 py-5 border-b-2">
        <img src="../src/assets/logo.svg" alt="">
        <p class="text-2xl font-semibold">Hope UI</p>
        <div class="absolute -right-3">
          <img src="../src/assets/strelochka.svg" alt="">
        </div>
      </div>
      <div>
       <ul>
        <li>Home</li>
        <ul>
          <li>
            Dashboard
            <img src="../src/assets/kvadrati.svg" alt="">
        </li>
        </ul>
       </ul>
      </div>
     </aside>
  </header>

  <RouterView />
</template>

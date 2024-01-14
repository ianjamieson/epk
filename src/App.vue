<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
// import amazon from '@/assets/image/amazon.png';


const navbarOpen = false;
</script>

<template>

    <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">


      some

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView /> -->
    <section class="h-screen w-screen">
        <header class="absolute px-12 py-4 w-full text-center top-0 left-0 bg-gradient-to-b from-white to-transparent h-32">
            <h1 class="text-2xl font-semibold">Ian Jamieson</h1>
        </header>
        <img class="object-cover w-full h-full object-right" src="./assets/image/we-dance.jpg" alt="Ian Jamieson stood on a dock with his guitar">
    </section>
    <section class="p-12 space-y-4">
        <h2
            class="font-bold text-gray-600 text-2xl md:text-4xl text-center"
        >
            Ian Jamieson on Spotify
        </h2>
        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/artist/2q2E2GheKlqjEBXPUEAcNR?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </section>

    <section class="p-12">
        <p
            class="font-semibold text-gray-800 text-2xl md:text-3xl xl:text-5xl text-center leading-tight"
        >
        Music for Ian is more than a passion; it's a heartfelt journey of expression and creativity.
        </p>
    </section>
    <section class="p-12">
        <img src="./assets/image/ian-jamieson.jpg" />
    </section>

    <section class="p-12">
        <p
            class="font-semibold text-gray-800 text-2xl md:text-3xl xl:text-5xl text-center leading-tight"
        >
            Ian's songs are deeply personal, blending melancholic acoustic guitar melodies with lyrics that come straight from the heart.
        </p>
    </section>
    <section class="p-12">
        <div class="relative w-full h-0 pb-[56.25%]">
            <iframe class="absolute top-0 left-0 w-full h-full" src="https://www.youtube-nocookie.com/embed/bzviAANSR6c?si=mfLCdTQLNmzOT3AB" title="Ian Jamieson - We Dance YouTube player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
    </section>

    <footer>

    </footer>





</template>
<script setup lang="ts">
//  import type { Attempt, Guess } from '../types/game';
// import { attempt } from './Attempt.vue';

//  let attempt = <Attempt>{};
//  let currentSelectedSong = <Song>{};
// let guesses = [...(attempt.guesses || [])];
</script>

<template>
  <div class="w-full px-0 sm:px-20 transition-all duration-20">
    <span class="text-center mx-auto w-full"
      >Listen to the intro, then find the correct artist & title in the list.
    </span>
  </div>
  <div>
    <input
      class="p-2 border-2 w-full text-gray-400 rounded-sm border-gray-600 bg-gray-900 hover:border-gray-400 focus:border-gray-400 outline-none transition-all duration-200"
      name="Spotify Playlist Input"
      placeholder="Spotify Playlist Link"
    />
  </div>
</template>

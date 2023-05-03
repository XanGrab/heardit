<script lang="ts">
import { Attempt } from "../types/game";

// const getColorOfAttempt = (index: number, attempts: number) => {
//   let color = "bg-black opacity-40";
//   if (attempts === index && !attempt.correct) {
//     color = "bg-blue-500";
//   } else if (attempts === index + 1 && attempt.correct) {
//     color = "bg-green-600";
//   } else if (
//     attempts > index &&
//     (attempt.guesses[index] as Guess).artistCorrect
//   ) {
//     color = "bg-amber-400";
//   } else if (attempts > index && !(attempt.guesses[index] as Guess).song) {
//     color = "bg-gray-500";
//   } else if (attempts > index) {
//     color = "bg-red-600";
//   }
//   return color;
// };

export let attempt: Attempt;
</script>

<template>
  <div class="max-w-3xl mx-auto flex h-3">
    <li></li>
  </div>
</template>

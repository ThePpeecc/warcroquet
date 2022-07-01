<template>
  <div class="menu flex flex-col">
    <div class="logo">
      <img src="gfx/login-logo.png">
    </div>
    <div class="link">
      <NuxtLink to="game" class="btn btn-yellow">Start Game</NuxtLink>
    </div>
    <div class="link">
      <NuxtLink to="rules" class="btn btn-yellow">Rules</NuxtLink>
    </div>
    <div class="link">
      <NuxtLink to="about" class="btn btn-yellow">About</NuxtLink>
    </div>
  </div>
</template>

<script lang="ts">

</script>

<style lang="scss">
  .menu {
    div {
      @apply flex justify-center;
    }
    .link {
      @apply mb-6;
    }
    .btn {
      @apply font-bold py-2 px-4 rounded w-56 block text-center;
    }

    .btn-yellow {
      @apply bg-yellow-300 text-green-900;
      &:hover {
        @apply bg-yellow-400;
      }
    }
  }
</style>

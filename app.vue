<template>
  <div>
    <nav class="navigation">
      <NuxtLink to="/">Homepage</NuxtLink>
      <NuxtLink to="/characters">Characters</NuxtLink>
      <NuxtLink to="https://laraveljutsu.net">Laravel Jutsu</NuxtLink>
    </nav>
    <NuxtPage />
  </div>
</template>

<style scoped>
.navigation {
  display: flex;
  gap: 5px;
}
</style>

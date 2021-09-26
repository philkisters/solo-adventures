<template>
  <div>
    <nav class="flex flex-row space-between">
      <div id="left">
        Logo
      </div>
      <div id="center" class="flex">
        <NuxtLink to="/">
          Start
        </NuxtLink>
        <NuxtLink to="/about">
          About
        </NuxtLink>
      </div>
      <div id="right">
        Profile
      </div>
    </nav>
    <Nuxt />
  </div>
</template>

<template>
  <header class="py-4 border-b">
    <nav class="flex container items-center">
      <NuxtLink
          to="/"
          class="flex gap-1 items-center"
      >
        <NuxtImg
            width="56px"
            src="/icon-green.png"
            format="webp"
            alt="logo"
        />
        <span
            class="text-3xl font-bold"
        >
          Nuxtcipes
        </span>
      </NuxtLink>
      <ul class="flex gap-6 ml-auto text-xl font-bold capitalize">
        <li>
          <NuxtLink
              to="/"
              class="hover:text-green-500"
              exact-active-class="text-green-500"
          >
            Home
          </NuxtLink>
        </li>
        <li>
          <NuxtLink
              to="/about"
              class="hover:text-green-500"
              exact-active-class="text-green-500"
          >
            About
          </NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script setup lang="ts">


</script>

<style scoped></style>